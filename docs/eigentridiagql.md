EigenTridiagonalQL



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Eigen Values](eigen_values.md)  /  [Tridiagonal Matrices](tridiagonalmatrices.md) / EigenTridiagonalQL

[![Previous](previous.png)](eigentridiagbisect.md) 
[![Next](next.png)](eigentridiagdcq.md)

EigenTridiagonalQL

Compute all eigenvalues of a symmetric tridiagonal matrix using the Pal-Walker-Kahan variant of the QL or QR algorithm (LAPACK function [STERF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sterf.md)).

Computing for type matrix<double>

```
bool  matrix::EigenTridiagonalQL(
   vector&               eigen_values        // vector of computed eigenvalues
   );
```

Computing for type matrix<float>

```
bool  matrixf::EigenTridiagonalQL(
   vectorf&              eigen_values        // vector of computed eigenvalues
   );
```

Parameters

eigen\_values

[out] Vector of eigenvalues.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

The input must be a symmetric matrix in the tridiagonal form.