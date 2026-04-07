PositionClose



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / PositionClose

[![Previous](previous.png)](ctradepositionmodify.md) 
[![Next](next.png)](ctradepositionclosepartial.md)

PositionClose

Closes a position by the specified symbol.

```
bool  PositionClose(
   const string  symbol,                  // symbol
   ulong         deviation=ULONG_MAX      // deviation
   )
```

Closes a position with the specified ticket.

```
bool  PositionClose(
   const ulong   ticket,                  // position ticket
   ulong         deviation=ULONG_MAX      // deviation
   )
```

Parameters

symbol

[in]  Name of trade instrument, by which it is intended to close position.

ticket

[in]  Ticket of a closed position.

deviation=[ULONG\_MAX](typeconstants.md)

[in] Maximal deviation from the current price (in points).

Return Value

true - successful check of the basic structures, otherwise - false.

Note

Successful completion of the PositionClose(...) method does not always mean successful execution of the trade operation. It is necessary to check the result of trade request (trade server return code) using [ResultRetcode()](ctraderesultretcode.md).

For the "netting" interpretation of positions ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_NETTING](accountinformation.md#enum_account_info_integer) and [ACCOUNT\_MARGIN\_MODE\_EXCHANGE](accountinformation.md#enum_account_info_integer)), only one [position](positionproperties.md) can exist for a [symbol](symbol.md) at any moment of time. This position is a result of one or more [deals](dealproperties.md). Do not confuse positions with valid [pending orders](orderproperties.md), which are also displayed on the Trading tab of the Toolbox window.

If individual positions are allowed ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_HEDGING](accountinformation.md#enum_account_info_integer)), multiple positions can be open for one symbol. In this case, PositionClose will close a position with the lowest ticket.