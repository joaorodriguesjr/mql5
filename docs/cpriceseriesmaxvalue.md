MaxValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CPriceSeries](cpriceseries.md) / MaxValue

[![Previous](previous.png)](cpriceseriesmaxindex.md) 
[![Next](next.png)](cindicator.md)

MaxValue

Gets the maximal value in the specified range.

```
virtual double  MaxValue(
   const int   start,     // size
   const int   count,     // amount
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

The maximal value of a series buffer in the specified range, or [EMPTY\_VALUE](otherconstants.md).

Note

The index of the found element is stored by index reference.