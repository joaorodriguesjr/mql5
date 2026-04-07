High



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / High

[![Previous](previous.png)](cexpertbaseopen.md) 
[![Next](next.png)](cexpertbaselow.md)

High

Gets the element of the High timeseries by index.

```
double  High(
   int    ind         // index
   )
```

Parameters

ind

[in]  Element index.

Return Value

If successful, it returns the numerical value of the High timeseries element with specified index, otherwise it returns EMPTY\_VALUE.

Note

The EMPTY\_VALUE is returned in two cases:

1. Timeseries is not used (the corresponding bit is not set).
2. Element index is out of range.