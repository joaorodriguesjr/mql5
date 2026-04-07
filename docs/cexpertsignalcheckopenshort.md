CheckOpenShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / CheckOpenShort

[![Previous](previous.png)](cexpertsignalcheckopenlong.md) 
[![Next](next.png)](cexpertsignalopenlongparams.md)

CheckOpenShort

Checks conditions to open a short position.

```
virtual bool  CheckOpenShort(
   double&    price,          // price
   double&    sl,             // Stop Loss
   double&    tp,             // Take Profit
   datetime&  expiration      // expiration
   )
```

Parameters

price

[in][out]  Variable for open price, passed by reference.

sl

[in][out]  Variable for Stop Loss price, passed by reference.

tp

[in][out]  Variable for Take Profit price, passed by reference.

expiration

[in][out]  Variable for expiration time, passed by reference (if necessary).

Return Value

true - condition is satisfied, otherwise - false.