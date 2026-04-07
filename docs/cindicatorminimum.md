Minimum



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / Minimum

[![Previous](previous.png)](cindicatorrefresh.md) 
[![Next](next.png)](cindicatorminvalue.md)

Minimum

Returns the index of minimal element of the specified buffer in a specified range.

```
int  Minimum(
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

Index of the minimal element of the specified buffer in a specified range.