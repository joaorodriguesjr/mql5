IsLowerHessenberg



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsLowerHessenberg

[![Previous](previous.png)](matrix_isupperhessenberg.md) 
[![Next](next.png)](matrix_istridiagonal.md)

IsLowerHessenberg

Check if a square matrix is lower Hessenberg matrix.

```
bool matrix::IsLowerHessenberg();
```

Return Value

True if square matrix is lower Hessenberg matrix.

Note

Lower Hessenberg matrix contains all zeros above the superdiagonal.

Tridiagonal matrix is Hessenberg matrix. Lower triangular matrix is lower Hessenberg matrix.

Lower Hessenberg matrix

```
   v  v  0  0  0  0
   v  v  v  0  0  0
   v  v  v  v  0  0
   v  v  v  v  v  0
   v  v  v  v  v  v
   v  v  v  v  v  v
```