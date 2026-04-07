OrdersTotal



[MQL5 Reference](index.md)  /  [Trade Functions](trading.md) / OrdersTotal

[![Previous](previous.png)](positiongetticket.md) 
[![Next](next.png)](ordergetticket.md)

OrdersTotal

Returns the number of current orders.

```
int  OrdersTotal();
```

Return Value

Value of the [int](integertypes.md) type.

Note

Do not confuse current [pending orders](orderproperties.md) with positions, which are also displayed on the "Trade" tab of the "Toolbox" of the client terminal. An order is a request to conduct a [transaction](enum_trade_request_actions.md), while a position is a result of one or more [deals](dealproperties.md).

For the "netting" interpretation of positions ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_NETTING](accountinformation.md#enum_account_info_integer) and [ACCOUNT\_MARGIN\_MODE\_EXCHANGE](accountinformation.md#enum_account_info_integer)), only one [position](positionproperties.md) can exist for a [symbol](symbol.md) at any moment of time. This position is a result of one or more [deals](dealproperties.md). Do not confuse positions with valid [pending orders](orderproperties.md), which are also displayed on the Trading tab of the Toolbox window.

If individual positions are allowed ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_HEDGING](accountinformation.md#enum_account_info_integer)), multiple positions can be open for one symbol.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get and print in the journal the number of active pending orders on the account
   int total=OrdersTotal();
   Print("Number of active pending orders on the account: ", total);
   /*
   result:
   Number of active pending orders on the account: 2
   */
  }
```

See also

[OrderSelect()](orderselect.md), [OrderGetTicket()](ordergetticket.md), [Order Properties](orderproperties.md)