BlasL2GeR



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [BLAS Level 2](blas_level2.md) / BlasL2GeR

[![Previous](previous.png)](blasl2trmv.md) 
[![Next](next.png)](blasl2gerc.md)

BlasL2GeR

Performs a rank-1 update of a general m-by-n matrix.

AU = alpha*x*y + A

BLAS functions [GER](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/ger.md), [GERU](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/geru.md).

Computing for type matrix<double>

```
bool  matrix::BlasL2GeR(
   double          alpha,         // scalar multiplier alpha
   vector&         X,             // vector X
   vector&         Y,             // vector Y
   matrix&         AU             // updated matrix A
   );
```

Computing for type matrix<float>

```
bool  matrixf::BlasL2GeR(
   float           alpha,         // scalar multiplier alpha
   vectorf&        X,             // vector X
   vectorf&        Y,             // vector Y
   matrixf&        AU             // updated matrix A
   );
```

Computing for type matrix<complex>

```
bool  matrixc::BlasL2GeR(
   complex         alpha,         // scalar multiplier alpha
   vectorc&        X,             // vector X
   vectorc&        Y,             // vector Y
   matrixc&        AU             // updated matrix A
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::BlasL2GeR(
   complexf        alpha,         // scalar multiplier alpha
   vectorcf&       X,             // vector X
   vectorcf&       Y,             // vector Y
   matrixcf&       AU             // updated matrix A
   );
```

Parameters

alpha

[in]  Scalar multiplier alpha.

X

[in]  Vector x of size m.

Y

[in]  Vector y of size n.

AU

[out]  Updated matrix A.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).