Maximum



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / Maximum

[![Previous](previous.png)](cindicatorminvalue.md) 
[![Next](next.png)](cindicatormaxvalue.md)

Maximum

Returns the index of maximal element of the specified buffer in a specified range.

```
int  Maximum(
   const int  buffer_num,     // buffer number
   const int  start,          // starting index
   const int  count           // number
   ) const
```

Parameters

buffer\_num

[in]  Buffer number to search the value in.

start

[in]  Search range initial index.

count

[in]  Search range size (number of elements).

Return Value

Index of the maximal element of the specified buffer in a specified range.