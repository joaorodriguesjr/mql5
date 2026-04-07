CheckReverseLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckReverseLong

[![Previous](previous.png)](cexpertsignalcloseshortparams.md) 
[![Next](next.png)](cexpertsignalcheckreverseshort.md)

CheckReverseLong

Checks conditions of a long position reversal.

```
virtual bool  CheckReverseLong(
   double&    price,          // price
   double&    sl,             // Stop Loss
   double&    tp,             // Take Profit
   datetime&  expiration      // expiration
   )
```

Parameters

price

[in][out]  Variable for price, passed by reference.

sl

[in][out]  Variable for Stop Loss price, passed by reference.

tp

[in][out]  Variable for Take Profit price, passed by reference.

expiration

[in][out]  Variable for expiration time, passed by reference (if necessary).

Return Value

true - condition is satisfied, otherwise - false.