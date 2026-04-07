InitTrade



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / InitTrade

[![Previous](previous.png)](cexpertinitmoney.md) 
[![Next](next.png)](cexpertdeinit.md)

InitTrade

Initializes the trade object.

```
virtual bool  InitTrade(
   ulong            magic,       // identifier
   CExpertTrade*    trade=NULL   // pointer
   )
```

Parameters

magic

[in]  Expert Advisor ID (will be used in trade requests).

trade

[in]  Pointer to trade object.

Return Value

true - successful, otherwise - false.