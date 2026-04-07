IsUpperBidiagonal



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsUpperBidiagonal

[![Previous](previous.png)](matrix_istridiagonal.md) 
[![Next](next.png)](matrix_islowerbidiagonal.md)

IsUpperBidiagonal

Check if a square matrix is upper bidiagonal.

```
bool matrix::IsUpperBidiagonal();
```

Return Value

True if square matrix is upper bidiagonal.

Note

Upper bidiagonal matrix contains all zeros under the main diagonal and above the superdiagonal.

Diagonal matrix is also bidiagonal.

Upper bidiagonal matrix

```
   v  v  0  0  0  0
   0  v  v  0  0  0
   0  0  v  v  0  0
   0  0  0  v  v  0
   0  0  0  0  v  v
   0  0  0  0  0  v
```