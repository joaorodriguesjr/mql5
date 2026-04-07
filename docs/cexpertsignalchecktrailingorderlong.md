CheckTrailingOrderLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckTrailingOrderLong

[![Previous](previous.png)](cexpertsignalcheckreverseshort.md) 
[![Next](next.png)](cexpertsignalchecktrailingordershort.md)

CheckTrailingOrderLong

Checks conditions to modify parameters of Buy Pending order.

```
virtual bool  CheckTrailingOrderLong(
   COrderInfo*    order,          // order
   double&        price           // price
   )
```

Parameters

order

[in]  Pointer to [COrderInfo](corderinfo.md) class object.

price

[in][out]  Variable for Stop Loss price.

Return Value

true - condition is satisfied, otherwise - false.