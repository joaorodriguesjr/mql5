CheckOpenLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneyFixedLot](cmoneyfixedlot.md) / CheckOpenLong

[![Previous](previous.png)](cmoneyfixedlotvalidationsettings.md) 
[![Next](next.png)](cmoneyfixedlotcheckopenshort.md)

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

[in]  Estimated Stop Loss order price.

Return Value

Trade volume for a long position.

Note

The function always returns the predefined fixed trade volume.