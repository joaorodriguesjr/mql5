CheckOpenLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneySizeOptimized](cmoneysizeoptimized.md) / CheckOpenLong

[![Previous](previous.png)](cmoneysizeoptimizedvalidationsettings.md) 
[![Next](next.png)](cmoneysizeoptimizedcheckopenshort.md)

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

Trade volume for long position.

Note

The function returns trade volume for a long position considering results of previous deals.