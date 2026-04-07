PositionModify



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / PositionModify

[![Previous](previous.png)](ctradepositionopen.md) 
[![Next](next.png)](ctradepositionclose.md)

PositionModify

Modifies the position parameters by specified symbol.

```
bool  PositionModify(
   const string  symbol,     // symbol
   double        sl,         // Stop Loss price
   double        tp          // Take Profit price
   )
```

Modifies position parameters by the specified ticket.

```
bool  PositionModify(
   const ulong   ticket,     // position ticket
   double        sl,         // Stop Loss price 
   double        tp          // Take Profit price
   )
```

Parameters

symbol

[in]  Name of trade instrument, by which it is intended to modify position.

ticket

[in]  Ticket of the position to be modified.

sl

[in] The new price by which the Stop Loss will trigger (or the previous value, if the change is not necessary).

tp

[in] The new price by which the Take Profit will trigger (or the previous value, if the change is not necessary).

Return Value

true - successful check of the basic structures, otherwise - false.

Note

Successful completion of the PositionModify(...) method does not always mean successful execution of the trade operation. It is necessary to check the result of trade request (trade server return code) using [ResultRetcode()](ctraderesultretcode.md).

For the "netting" interpretation of positions ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_NETTING](accountinformation.md#enum_account_info_integer) and [ACCOUNT\_MARGIN\_MODE\_EXCHANGE](accountinformation.md#enum_account_info_integer)), only one [position](positionproperties.md) can exist for a [symbol](symbol.md) at any moment of time. This position is a result of one or more [deals](dealproperties.md). Do not confuse positions with valid [pending orders](orderproperties.md), which are also displayed on the Trading tab of the Toolbox window.

If individual positions are allowed ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_HEDGING](accountinformation.md#enum_account_info_integer)), multiple positions can be open for one symbol. In this case, PositionModify will modify the position with the lowest ticket.