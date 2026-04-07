IsLowerBidiagonal



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsLowerBidiagonal

[![Previous](previous.png)](matrix_isupperbidiagonal.md) 
[![Next](next.png)](matrix_isdiagonal.md)

IsLowerBidiagonal

Check if a square matrix is lower bidiagonal.

```
bool matrix::IsLowerBidiagonal();
```

Return Value

True if square matrix is lower bidiagonal.

Note

Lower bidiagonal matrix contains all zeros under the subdiagonal and above the main diagonal.

Diagonal matrix is also bidiagonal.

Lower bidiagonal matrix

```
   v  0  0  0  0  0
   v  v  0  0  0  0
   0  v  v  0  0  0
   0  0  v  v  0  0
   0  0  0  v  v  0
   0  0  0  0  v  v
```