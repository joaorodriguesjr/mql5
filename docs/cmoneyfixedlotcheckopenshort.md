CheckOpenShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneyFixedLot](cmoneyfixedlot.md) / CheckOpenShort

[![Previous](previous.png)](cmoneyfixedlotcheckopenlong.md) 
[![Next](next.png)](cmoneyfixedmargin.md)

CheckOpenShort

Gets trade volume for a short position.

```
virtual double  CheckOpenShort(
   double  price,     // price
   double  sl         // Stop Loss price
   )
```

Parameters

price

[in] Estimated open price.

sl

[in]  Estimated Stop Loss order price.

Return Value

Trade volume for a short position.

Note

The function always returns the predefined fixed trade volume.