CheckOpenLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneyFixedRisk](cmoneyfixedrisk.md) / CheckOpenLong

[![Previous](previous.png)](cmoneyfixedrisk.md) 
[![Next](next.png)](cmoneyfixedriskcheckopenshort.md)

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

The function returns trade volume for a long position with a fixed predefined risk level. The risk is defined by Percent parameter of [CExpertMoney](cexpertmoney.md) base class.