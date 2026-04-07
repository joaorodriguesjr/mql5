PositionsTotal



[MQL5 Reference](index.md)  /  [Trade Functions](trading.md) / PositionsTotal

[![Previous](previous.png)](ordersendasync.md) 
[![Next](next.png)](positiongetsymbol.md)

PositionsTotal

Returns the number of open positions.

```
int  PositionsTotal();
```

Return Value

Value of [int](integertypes.md) type.

Note

For the "netting" interpretation of positions ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_NETTING](accountinformation.md#enum_account_info_integer) and [ACCOUNT\_MARGIN\_MODE\_EXCHANGE](accountinformation.md#enum_account_info_integer)), only one [position](positionproperties.md) can exist for a [symbol](symbol.md) at any moment of time. This position is a result of one or more [deals](dealproperties.md). Do not confuse positions with valid [pending orders](orderproperties.md), which are also displayed on the Trading tab of the Toolbox window.

If individual positions are allowed ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_HEDGING](accountinformation.md#enum_account_info_integer)), multiple positions can be open for one symbol.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get and print the number of open positions on the account in the journal
   int total=PositionsTotal();
   Print("Number of open positions on account: ", total);
   /*
   result:
   Number of open positions on account: 2
   */
  }
```

See also

[PositionGetSymbol()](positiongetsymbol.md), [PositionSelect()](positionselect.md), [Position Properties](positionproperties.md)