InitMoney



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / InitMoney

[![Previous](previous.png)](cexpertinittrailing.md) 
[![Next](next.png)](cexpertinittrade.md)

InitMoney

Initializes the money management object.

```
virtual bool  InitMoney(
   CExpertMoney*     money=NULL,        // pointer
   )
```

Parameters

money

[in]  Pointer to [CExpertMoney](cexpertmoney.md) class object (or its descendant).

Return Value

true - successful, otherwise - false.

Note

If money is NULL, the [CExpertMoney](cexpertmoney.md) class will be used for initialization (it uses the minimum lot).