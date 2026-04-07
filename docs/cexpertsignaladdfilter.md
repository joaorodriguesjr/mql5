AddFilter



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / AddFilter

[![Previous](previous.png)](cexpertsignalinitindicators.md) 
[![Next](next.png)](cexpertsignalcheckopenlong.md)

AddFilter

Adds a filter to the composite signal.

```
virtual bool  AddFilter(
   CExpertSignal*  filter    // pointer
   )
```

Parameters

indicators

[in]  Pointer to filter object.

Return Value

true - successful, otherwise - false.