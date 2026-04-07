CheckOpenLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneyNone](cmoneynone.md) / CheckOpenLong

[![Previous](previous.png)](cmoneynonevalidationsettings.md) 
[![Next](next.png)](cmoneynonecheckopenshort.md)

CheckOpenLong

Gets trade volume for a long position.

```
virtual double  CheckOpenLong(
   double  price,     // price
   double  sl         // Stop Loss price
   )
```

Parameters

price

[in]  Estimated open price.

sl

[in]  Estimated Stop Loss price.

Return Value

Trade volume for a long position.

Note

The function always returns the minimal lot size.