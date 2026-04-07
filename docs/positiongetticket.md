PositionGetTicket



[MQL5 Reference](index.md)  /  [Trade Functions](trading.md) / PositionGetTicket

[![Previous](previous.png)](positiongetstring.md) 
[![Next](next.png)](orderstotal.md)

PositionGetTicket

The function returns the ticket of a position with the specified index in the list of open positions and automatically selects the position to work with using functions [PositionGetDouble](positiongetdouble.md), [PositionGetInteger](positiongetinteger.md), [PositionGetString](positiongetstring.md).

```
ulong  PositionGetTicket(
   int  index      // The number of a position in the list
   );
```

Parameters

index

[in]  The index of a position in the list of open positions, numeration starts with 0.

Return Value

The ticket of the position. Returns 0 if the function fails.

Note

For the "netting" interpretation of positions ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_NETTING](accountinformation.md#enum_account_info_integer) and [ACCOUNT\_MARGIN\_MODE\_EXCHANGE](accountinformation.md#enum_account_info_integer)), only one [position](positionproperties.md) can exist for a [symbol](symbol.md) at any moment of time. This position is a result of one or more [deals](dealproperties.md). Do not confuse positions with valid [pending orders](orderproperties.md), which are also displayed on the Trading tab of the Toolbox window.

If individual positions are allowed ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_HEDGING](accountinformation.md#enum_account_info_integer)), multiple positions can be open for one symbol.

To ensure receipt of fresh data about a position, it is recommended to call [PositionSelect()](positionselect.md) right before referring to them.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- in a loop by all account positions
   int total=PositionsTotal();
   for(int i=0; i<total; i++)
     {
      //--- get the ticket of the next position by automatically selecting a position to access its properties
      ulong ticket=PositionGetTicket(i);
      if(ticket==0)
         continue;
      
      //--- get the position type and display the description of the selected position to the journal
      string type=(PositionGetInteger(POSITION_TYPE)==POSITION_TYPE ? "Buy" : "Sell");
      PrintFormat("[%d] Selected position %s #%I64u", i, type, ticket);
     }
   /*
   result:
   [0] Selected position Sell #2810802718
   [1] Selected position Buy #2810802919
   */
  }
```

See also

[PositionGetSymbol()](positiongetsymbol.md), [PositionSelect()](positionselect.md), [Position Properties](positionproperties.md)