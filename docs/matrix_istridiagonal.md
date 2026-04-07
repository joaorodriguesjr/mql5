IsTridiagonal



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsTridiagonal

[![Previous](previous.png)](matrix_islowerhessenberg.md) 
[![Next](next.png)](matrix_isupperbidiagonal.md)

IsTridiagonal

Check if a square matrix is tridiagonal.

```
bool matrix::IsTridiagonal();
```

Return Value

True if square matrix is tridiagonal.

Note

Tridiagonal matrix contains all zeros under the subdiagonal and above the superdiagonal.

Bidiagonal matrix upper or lower is also tridiagonal.

Tridiagonal matrix

```
   v  v  0  0  0  0
   v  v  v  0  0  0
   0  v  v  v  0  0
   0  0  v  v  v  0
   0  0  0  v  v  v
   0  0  0  0  v  v
```