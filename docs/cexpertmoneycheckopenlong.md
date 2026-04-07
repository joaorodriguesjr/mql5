CheckOpenLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertMoney](cexpertmoney.md) / CheckOpenLong

[![Previous](previous.png)](cexpertmoneyvalidationsettings.md) 
[![Next](next.png)](cexpertmoneycheckopenshort.md)

CheckOpenLong

Gets the volume for a long position.

```
virtual double  CheckOpenLong(
   double  price,     // price
   double  sl         // Stop Loss
   )
```

Parameters

price

[in]  Opening price of a long position.

sl

[in]  Stop Loss price of a long position.

Return Value

Trade volume for a long position.