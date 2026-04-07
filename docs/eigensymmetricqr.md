EigenSymmetricQR



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Eigen Values](eigen_values.md)  /  [Symmetric Matrices](symmetric_matrices.md) / EigenSymmetricQR

[![Previous](previous.png)](eigensymmetricdc.md) 
[![Next](next.png)](eigensymmetricrobust.md)

EigenSymmetricQR

Compute eigenvalues and eigenvectors of a symmetric or Hermitian (complex conjugated) matrix using the QR algorithm (LAPACK functions [SYEV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/syev.md), [HEEV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/heev.md)).

Computing for type matrix<double>

```
bool  matrix::EigenSymmetricQR(
   ENUM_EIG_VALUES       jobv,               // compute eigenvectors or not
   vector&               eigen_values,       // vector of computed eigenvalues
   matrix&               eigen_vectors       // matrix of computed eigenvectors
   );
```

Computing for type matrix<float>

```
bool  matrixf::EigenSymmetricQR(
   ENUM_EIG_VALUES       jobv,               // compute eigenvectors or not
   vectorf&              eigen_values,       // vector of computed eigenvalues
   matrixf&              eigen_vectors       // matrix of computed eigenvectors
   );
```

Computing for type matrix<complex>

```
bool  matrixc::EigenSymmetricQR(
   ENUM_EIG_VALUES       jobv,               // compute eigenvectors or not
   vector&               eigen_values,       // vector of computed eigenvalues
   matrixc&              eigen_vectors       // matrix of computed eigenvectors
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::EigenSymmetricQR(
   ENUM_EIG_VALUES       jobv,               // compute eigenvectors or not
   vectorf&              eigen_values,       // vector of computed eigenvalues
   matrixcf&             eigen_vectors       // matrix of computed eigenvectors
   );
```

Parameters

jobv

[in] [ENUM\_EIG\_VALUES](eigensymmetricdc.md#enum_eig_values) enumeration value which determines the method for computing eigenvectors.

eigen\_values

[out] Vector of eigenvalues.

eigen\_vectors

[out] Matrix of eigenvectors.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

Computation depends on the value of the jobv parameter.

When jobv = EIGVALUES\_V, eigenvectors and eigenvalues are calculated.

If EIGVALUES\_N is set, eigenvectors are not calculated. Only eigenvalues are computed.

The input can be a symmetric (Hermitian), [upper triangular](matrix_triu.md) or [lower triangular](matrix_tril.md) matrix. Triangular matrices are assumed to be symmetric (Hermitian conjugated).

 

ENUM\_EIG\_VALUES

An enumeration defining the need to compute eigenvectors.

| ID | Description |
| --- | --- |
| EIGVALUES\_V | Eigenvectors and eigenvalues are calculated. |
| EIGVALUES\_N | Only eigenvalues are computed, without vectors. |