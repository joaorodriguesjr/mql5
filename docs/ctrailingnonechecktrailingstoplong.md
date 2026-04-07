CheckTrailingStopLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md)  /  [CTrailingNone](ctrailingnone.md) / CheckTrailingStopLong

[![Previous](previous.png)](ctrailingnone.md) 
[![Next](next.png)](ctrailingnonechecktrailingstopshort.md)

CheckTrailingStopLong

Checks Trailing Stop conditions of a long position.

```
virtual bool  CheckTrailingStopLong(
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

The function always returns false.