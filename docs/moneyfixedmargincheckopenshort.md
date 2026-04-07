CheckOpenShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneyFixedMargin](cmoneyfixedmargin.md) / CheckOpenShort

[![Previous](previous.png)](moneyfixedmargincheckopenlong.md) 
[![Next](next.png)](cmoneyfixedrisk.md)

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

[in]  Estimated open price.

sl

[in]  Estimated Stop Loss price.

Return Value

Trade volume for a short position.

Note

The function returns trade volume for a short position with a predefined fixed margin. The margin is defined by Percent parameter of [CExpertMoney](cexpertmoney.md) base class.