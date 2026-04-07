CheckReverseShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckReverseShort

[![Previous](previous.png)](cexpertsignalcheckreverselong.md) 
[![Next](next.png)](cexpertsignalchecktrailingorderlong.md)

CheckReverseShort

Checks conditions of a short position reversal.

```
virtual bool  CheckReverseShort(
   double&    price,          // price
   double&    sl,             // Stop Loss
   double&    tp,             // Take Profit
   datetime&  expiration      // expiration
   )
```

Parameters

price

[in][out]  Variable for reversal price, passed by reference.

sl

[in][out]  Variable for Stop Loss price, passed by reference.

tp

[in][out]  Variable for Take Profit price, passed by reference.

expiration

[in][out]  Variable for expiration time, passed by reference (if necessary).

Return Value

true - condition is satisfied, otherwise - false.