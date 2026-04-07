IsUpperHessenberg



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsUpperHessenberg

[![Previous](previous.png)](matrix_istrapeziodal.md) 
[![Next](next.png)](matrix_islowerhessenberg.md)

IsUpperHessenberg

Check if a square matrix is upper Hessenberg matrix.

```
bool matrix::IsUpperHessenberg();
```

Return Value

True if square matrix is upper Hessenberg matrix.

Note

Upper Hessenberg matrix contains all zeros under the subdiagonal.

Tridiagonal matrix is Hessenberg matrix. Upper triangular matrix is upper Hessenberg matrix.

Upper Hessenberg matrix

```
   v  v  v  v  v  v
   v  v  v  v  v  v
   0  v  v  v  v  v
   0  0  v  v  v  v
   0  0  0  v  v  v
   0  0  0  0  v  v
```