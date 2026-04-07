GetData



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CPriceSeries](cpriceseries.md) / GetData

[![Previous](previous.png)](cpriceseriesbufferresize.md) 
[![Next](next.png)](cpriceseriesrefresh.md)

GetData

Gets the specified series buffer element.

```
double  GetData(
   const int  index      // index
   ) const
```

Parameters

index

[in]  Index of a buffer element.

Return Value

The series buffer element, or [EMPTY\_VALUE](otherconstants.md).