BlasL2SyMV



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [BLAS Level 2](blas_level2.md) / BlasL2SyMV

[![Previous](previous.png)](blasl2gemv.md) 
[![Next](next.png)](blasl2hemv.md)

BlasL2SyMV

Computes a matrix-vector product for a symmetric n-by-n matrix.

y = alpha*A*x + beta*y

BLAS function [SYMV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/symv-002.md).

Computing for type matrix<double>

```
bool  matrix::BlasL2SyMV(
   double          alpha,         // scalar multiplier alpha
   vector&         X,             // vector X
   double          beta,          // scalar multiplier beta
   vector&         Y              // result vector Y
   );
```

Computing for type matrix<float>

```
bool  matrixf::BlasL2SyMV(
   float           alpha,         // scalar multiplier alpha
   vectorf&        X,             // vector X
   float           beta,          // scalar multiplier beta
   vectorf&        Y              // result vector Y
   );
```

Parameters

alpha

[in]  Scalar multiplier alpha.

X

[in]  Vector x of size n.

beta

[in]  Scalar multiplier beta.

Y

[in, out]  Result vector y of size n. If beta is not zero, then vector Y should contain actual data before entry.If vector size differs from n, then vector Y will be resized and zeroed.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

The input can be a symmetric, upper triangular or lower triangular matrix. Triangular matrices are assumed to be symmetric.