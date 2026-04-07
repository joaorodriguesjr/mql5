InitSignal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / InitSignal

[![Previous](previous.png)](cexpertmagic.md) 
[![Next](next.png)](cexpertinittrailing.md)

InitSignal

Initializes trading signal object.

```
virtual bool  InitSignal(
   CExpertSignal*     signal=NULL,        // pointer
   )
```

Parameters

signal

[in]  Pointer to [CExpertSignal](cexpertsignal.md) class object (or its descendant).

Return Value

true - successful, otherwise - false.

Note

If signal is NULL, the [CExpertSignal](cexpertsignal.md) class will be used for initialization (it does nothing).