IsScalar



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsScalar

[![Previous](previous.png)](matrix_isdiagonal.md) 
[![Next](next.png)](matrix_solves.md)

IsScalar

Check if a square matrix is scalar matrix.

```
bool matrix::IsScalar();
```

Return Value

True if square matrix is scalar matrix.

Note

Scalar matrix is a diagonal matrix, where all diagonal elements are equal.

Zero matrix of n-by-n size is scalar matrix. Square [identity matrix](matrix_identity.md) is scalar matrix.

Scalar matrix

```
   I  0  0  0  0  0
   0  I  0  0  0  0
   0  0  I  0  0  0
   0  0  0  I  0  0
   0  0  0  0  I  0
   0  0  0  0  0  I
```