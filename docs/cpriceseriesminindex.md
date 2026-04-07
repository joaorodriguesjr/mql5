MinIndex



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CPriceSeries](cpriceseries.md) / MinIndex

[![Previous](previous.png)](cpriceseriesrefresh.md) 
[![Next](next.png)](cpriceseriesminvalue.md)

MinIndex

Gets the index of minimal value in the specified range.

```
virtual int  MinIndex(
   const int  start,     // size
   const int  count      // number
   ) const
```

Parameters

start

[in]  Search range initial index.

count

[in]  Search range size (number of elements).

Return Value

The index of minimal value of a series buffer in the specified range, or -1.