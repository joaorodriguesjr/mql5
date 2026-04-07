ReplaceNan



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Manipulations](matrix_manipulations.md) / ReplaceNan

[![Previous](previous.png)](matrix_hasnan.md) 
[![Next](next.png)](matrix_replacetozero.md)

ReplaceNan

Replace [NaN](double.md) values in a matrix/vector with the specified value and return the number of elements replaced.

```
ulong vector::ReplaceNan(
  const double   value      // new value
   );
 
ulong vectorf::ReplaceNan(
  const float    value      // new value
   );
 
ulong matrix::ReplaceNan(
  const double   value      // new value
   );
 
ulong matrixf::ReplaceNan(
  const float    value      // new value
   );
```

Parameters

value

[in]  New value to replace NaN elements in the matrix/vector.

Return Value

The number of matrix/vector NaN elements that were replaced by new value.