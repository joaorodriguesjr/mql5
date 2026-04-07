EigenTridiagonalDCQ



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Eigen Values](eigen_values.md)  /  [Tridiagonal Matrices](tridiagonalmatrices.md) / EigenTridiagonalDCQ

[![Previous](previous.png)](eigentridiagql.md) 
[![Next](next.png)](eigentridiagqrq.md)

EigenTridiagonalDCQ

Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the divide-and-conquer algorithm (LAPACK function [STEDC](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/stedc.md)). Unlike [EigenTridiagonalDC](eigentridiagposdefq.md), this method can be used to compute the eigenvectors of the original symmetric matrix. A symmetric matrix can be reduced to tridiagonal form using the [ReduceSymmetricToTridiagonal](reducesymmetrictotridiagonal.md) method. The orthogonal matrix Q obtained from this transformation is then used to compute the eigenvectors of the original symmetric matrix.

Computing for type matrix<double>

```
bool  matrix::EigenTridiagonalDCQ(
   ENUM_EIGTRIDIAG_Z     compv,              // compute eigenvectors or not
   matrix&               Q,                  // orthogonal matrix used in the reduction to tridiagonal form
   vector&               eigen_values,       // vector of computed eigenvalues
   matrix&               eigen_vectors       // matrix of computed eigenvectors
   );
```

Computing for type matrix<float>

```
bool  matrixf::EigenTridiagonalDCQ(
   ENUM_EIGTRIDIAG_Z     compv,              // compute eigenvectors or not
   matrixf&              Q,                  // orthogonal matrix used in the reduction to tridiagonal form
   vectorf&              eigen_values,       // vector of computed eigenvalues
   matrixf&              eigen_vectors       // matrix of computed eigenvectors
   );
```

Computing for type matrix<complex>

```
bool  matrixc::EigenTridiagonalDCQ(
   ENUM_EIGTRIDIAG_Z     compv,              // compute eigenvectors or not
   matrixc&              Q,                  // orthogonal matrix used in the reduction to tridiagonal form
   vector&               eigen_values,       // vector of computed eigenvalues
   matrixc&              eigen_vectors       // matrix of computed eigenvectors
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::EigenTridiagonalDCQ(
   ENUM_EIGTRIDIAG_Z     compv,              // compute eigenvectors or not
   matrixcf&             Q,                  // orthogonal matrix used in the reduction to tridiagonal form
   vectorf&              eigen_values,       // vector of computed eigenvalues
   matrixcf&             eigen_vectors       // matrix of computed eigenvectors
   );
```

Parameters

compv

[in]  ENUM\_EIGTRIDIAG\_Z enumeration value which determines the method for computing eigenvectors.

Q

[in]  Orthogonal matrix Q produced by method [ReflectTridiagonalToQ](reflecttridiagonaltoq.md).

eigen\_values

[out] Vector of eigenvalues.

eigen\_vectors

[out] Matrix of eigenvectors.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

Computation depends on the value of the compv parameter.

When compv = EIGCOMPZ\_N, compute eigenvalues only, eigenvectors are not calculated.

If EIGCOMPZ\_V is set, eigenvalues are computed and eigenvectors of original symmetric matrix are calculated also.

If EIGCOMPZ\_I is set, eigenvalues are computed and eigenvectors of tridiagonal matrix are calculated also.

The input must be a symmetric matrix in the tridiagonal form.

 

ENUM\_EIGTRIDIAG\_Z

An enumeration that specifies whether to calculate eigenvectors.

| ID | Description |
| --- | --- |
| EIGCOMPZ\_N | 'N': Compute eigenvalues only |
| EIGCOMPZ\_V | 'V': Compute eigenvectors of original symmetric matrix also |
| EIGCOMPZ\_I | 'I': Compute eigenvectors of tridiagonal matrix also |