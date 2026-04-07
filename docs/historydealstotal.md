HistoryDealsTotal



[MQL5 Reference](index.md)  /  [Trade Functions](trading.md) / HistoryDealsTotal

[![Previous](previous.png)](historydealselect.md) 
[![Next](next.png)](historydealgetticket.md)

HistoryDealsTotal

Returns the number of deal in history. Prior to calling HistoryDealsTotal(), first it is necessary to receive the history of deals and orders using the [HistorySelect()](historyselect.md) or [HistorySelectByPosition()](historyselectbyposition.md) function.

```
int  HistoryDealsTotal();
```

Return Value

Value of the [int](integertypes.md) type.

Note

Do not confuse [orders](orderproperties.md), [deals](dealproperties.md) and [positions](positionproperties.md). Each deal is the result of the execution of an order, each position is the summary result of one or more deals.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- request all the existing history on the account
   if(!HistorySelect(0, TimeCurrent()))
     {
      Print("HistorySelect() failed. Error ", GetLastError());
      return;
     }
 
//--- get the number of deals in the list and display it in the journal
   int total=HistoryDealsTotal();
   Print("Number of historical deals on the account: ", total);
   /*
   result:
   Number of historical deals on the account: 339
   */
  }
```

See also

[HistorySelect()](historyselect.md), [HistoryDealGetTicket()](historydealgetticket.md), [Deal Properties](dealproperties.md)