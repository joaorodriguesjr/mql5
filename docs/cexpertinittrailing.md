InitTrailing



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / InitTrailing

[![Previous](previous.png)](cexpertinitsignal.md) 
[![Next](next.png)](cexpertinitmoney.md)

InitTrailing

Initializes trailing stop object.

```
virtual bool  InitTrailing(
   CExpertTrailing*     trailing=NULL,        // pointer
   )
```

Parameters

trailing

[in]  Pointer to [CExpertTrailing](cexperttrailing.md) class object (or its descendant).

Return Value

true - successful, otherwise - false.

Note

If trailing is NULL, the [ExpertTrailing](cexperttrailing.md) class will be used for initialization (it does nothing).