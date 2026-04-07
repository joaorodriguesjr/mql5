IsHermitian



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Matrix Classification](matrix_classification.md) / IsHermitian

[![Previous](previous.png)](matrix_issymmetric.md) 
[![Next](next.png)](matrix_isuppertriangular.md)

IsHermitian

Check if a square complex matrix is Hermitian.

```
bool matrixc::IsHermitian();
```

Return Value

True if square complex matrix is Hermitian.

Note

Zero matrix of n-by-n size is Hermitian. Diagonal matrix is Hermitian only if all elements of the diagonal have an imaginary part equal to 0.

This method can be apply to the real (non-complex) matrix. In this case symmetry is checked.