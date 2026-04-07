CheckCloseShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckCloseShort

[![Previous](previous.png)](cexpertsignalcheckcloselong.md) 
[![Next](next.png)](cexpertsignalcloselongparams.md)

CheckCloseShort

Checks conditions to close a short position.

```
virtual bool  CheckCloseShort(
   double&  price      // price
   )
```

Parameters

price

[in][out]  Variable for close price, passed by reference.

Return Value

true - condition is satisfied, otherwise - false.