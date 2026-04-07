CheckTrailingStopShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md)  /  [CTrailingMA](ctrailingma.md) / CheckTrailingStopShort

[![Previous](previous.png)](ctrailingmachecktrailingstoplong.md) 
[![Next](next.png)](ctrailingnone.md)

CheckTrailingStopShort

Checks Trailing Stop conditions of a short position.

```
virtual bool  CheckTrailingStopShort(
   CPositionInfo*  position,     // pointer
   double&         sl,           // reference
   double&         tp            // reference
   )
```

Parameters

position

[in]  Pointer to [CPositionInfo](cpositioninfo.md) object.

sl

[in][out]  Reference to variable for Stop Loss price.

tp

[in][out]  Reference to variable for Take Profit price.

Return Value

true - conditions are satisfied, otherwise - false.

Note

First it calculates the minimal allowed Stop Loss price closest to the current price and calculates Stop Loss price using the values of moving average indicator of the previous (completed) bar. If position already has Stop Loss price, its value is assumed as a base price, otherwise the base price is the open price of the position. If the calculated Stop Loss price is lower than base price and higher than minimal allowed Stop Loss price, it suggests to set new Stop Loss price.