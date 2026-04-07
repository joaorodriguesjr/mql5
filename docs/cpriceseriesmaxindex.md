MaxIndex



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CPriceSeries](cpriceseries.md) / MaxIndex

[![Previous](previous.png)](cpriceseriesminvalue.md) 
[![Next](next.png)](cpriceseriesmaxvalue.md)

MaxIndex

Gets the index of maximal value in the specified range.

```
virtual int  MaxIndex(
   const int  start,     // index
   const int  count      // number
   ) const
```

Parameters

start

[in]  Search range initial index.

count

[in]  Search range size (number of elements).

Return Value

The index of the maximal value of the series buffer in the specified range, or -1.