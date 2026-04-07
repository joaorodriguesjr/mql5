CheckTrailingOrderShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckTrailingOrderShort

[![Previous](previous.png)](cexpertsignalchecktrailingorderlong.md) 
[![Next](next.png)](cexpertsignallongcondition.md)

CheckTrailingOrderShort

Checks conditions to modify parameters of Sell Pending order.

```
virtual bool  CheckTrailingOrderShort(
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