CheckReverse



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertMoney](cexpertmoney.md) / CheckReverse

[![Previous](previous.png)](cexpertmoneycheckopenshort.md) 
[![Next](next.png)](cexpertmoneycheckclose.md)

CheckReverse

Gets the volume for reverse of the position.

```
virtual double  CheckReverse(
   CPositionInfo*  position,     // pointer
   double          sl            // Stop Loss
   )
```

Parameters

position

[in]  Pointer to [CPositionInfo](cpositioninfo.md) class object.

sl

[in]  Stop Loss price.

Return Value

Volume for reverse of the position.