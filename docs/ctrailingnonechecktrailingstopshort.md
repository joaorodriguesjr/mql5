CheckTrailingStopShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md)  /  [CTrailingNone](ctrailingnone.md) / CheckTrailingStopShort

[![Previous](previous.png)](ctrailingnonechecktrailingstoplong.md) 
[![Next](next.png)](ctrailingpsar.md)

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

The function always returns false.