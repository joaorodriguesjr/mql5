MinValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CPriceSeries](cpriceseries.md) / MinValue

[![Previous](previous.png)](cpriceseriesminindex.md) 
[![Next](next.png)](cpriceseriesmaxindex.md)

MinValue

Gets the minimal value in the specified range.

```
virtual double  MinValue(
   const int   start,     // size
   const int   count,     // number
   int&        index      // reference 
   ) const
```

Parameters

start

[in]  Search range initial index.

count

[in]  Search range size (number of elements).

index

[out]  Reference to the variable for placing the found element's index value.

Return Value

The minimal value of the series buffer in the specified range, or [EMPTY\_VALUE](otherconstants.md).

Note

The index of the found element is stored by index reference.