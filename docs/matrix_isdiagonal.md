IsDiagonal



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsDiagonal

[![Previous](previous.png)](matrix_islowerbidiagonal.md) 
[![Next](next.png)](matrix_isscalar.md)

IsDiagonal

Check if a square matrix is diagonal.

```
bool matrix::IsDiagonal();
```

Return Value

True if square matrix is diagonal.

Note

Diagonal matrix contains all zeros under and above the main diagonal.

Zero matrix of n-by-n size is diagonal.

Diagonal matrix

```
   v  0  0  0  0  0
   0  v  0  0  0  0
   0  0  v  0  0  0
   0  0  0  v  0  0
   0  0  0  0  v  0
   0  0  0  0  0  v
```