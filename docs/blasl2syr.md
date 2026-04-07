BlasL2SyR



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [BLAS Level 2](blas_level2.md) / BlasL2SyR

[![Previous](previous.png)](blasl2gerc.md) 
[![Next](next.png)](blasl2her.md)

BlasL2SyR

Performs a rank-1 update of a symmetric n-by-n matrix.

AU = alpha * x * x**T + A

BLAS function [SYR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/syr-001.md).

Computing for type matrix<double>

```
bool  matrix::BlasL2SyR(
   double          alpha,         // scalar multiplier alpha
   vector&         X,             // vector X
   matrix&         AU             // updated matrix A
   );
```

Computing for type matrix<float>

```
bool  matrixf::BlasL2SyR(
   float           alpha,         // scalar multiplier alpha
   vectorf&        X,             // vector X
   matrixf&        AU             // updated matrix A
   );
```

Parameters

alpha

[in]  Scalar multiplier alpha.

X

[in]  Vector x of size n.

AU

[out]  Updated matrix A.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

The input can be a symmetric, upper triangular or lower triangular matrix. Triangular matrices are assumed to be symmetric.