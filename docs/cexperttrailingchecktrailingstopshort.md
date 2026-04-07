CheckTrailingStopShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertTrailing](cexperttrailing.md) / CheckTrailingStopShort

[![Previous](previous.png)](cexperttrailingchecktrailingstoplong.md) 
[![Next](next.png)](cexpertmoney.md)

CheckTrailingStopShort

Checks conditions to modify parameters of a short position.

```
virtual bool  CheckTrailingStopShort(
   CPositionInfo*  position,     // pointer
   double&         sl,           // Stop Loss
   double&         tp            // Take Profit
   )
```

Parameters

position

[in]  Pointer to [CPositionInfo](cpositioninfo.md) class object.

sl

[in][out]  Variable for Stop Loss price, passed by reference.

tp

[in][out]  Variable for Take Profit price, passed by reference.

Return Value

true - condition is satisfied, otherwise - false.

Note

Base class method always returns false.