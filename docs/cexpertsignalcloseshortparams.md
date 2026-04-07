CloseShortParams



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CloseShortParams

[![Previous](previous.png)](cexpertsignalcloselongparams.md) 
[![Next](next.png)](cexpertsignalcheckreverselong.md)

CloseShortParams

Sets parameters to close a short position.

```
virtual bool  CloseShortParams(
   double&    price          // price
   )
```

Parameters

price

[in][out]  Variable for close price, passed by reference.

Return Value

true - successful, otherwise - false.