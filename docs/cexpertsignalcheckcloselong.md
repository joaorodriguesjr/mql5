CheckCloseLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckCloseLong

[![Previous](previous.png)](cexpertsignalopenshortparams.md) 
[![Next](next.png)](cexpertsignalcheckcloseshort.md)

CheckCloseLong

Checks conditions to close a long position.

```
virtual bool  CheckCloseLong(
   double&  price      // price
   )
```

Parameters

price

[in][out]  Variable for close price, passed by reference.

Return Value

true - condition is satisfied, otherwise - false.