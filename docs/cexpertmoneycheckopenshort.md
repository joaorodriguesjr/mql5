CheckOpenShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertMoney](cexpertmoney.md) / CheckOpenShort

[![Previous](previous.png)](cexpertmoneycheckopenlong.md) 
[![Next](next.png)](cexpertmoneycheckreverse.md)

CheckOpenShort

Gets the volume for a short position.

```
virtual double  CheckOpenShort(
   double  price,     // price
   double  sl         // Stop Loss
   )
```

Parameters

price

[in]  Opening price for a short position.

sl

[in]  Stop Loss price of a short position.

Return Value

Trade volume for a short position.