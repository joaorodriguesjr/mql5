FactorizationCholesky



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Factorizations](factorizations.md) / FactorizationCholesky

[![Previous](previous.png)](factorizationldlsytridpd.md) 
[![Next](next.png)](factorizationcholeskysyps.md)

FactorizationCholesky

Computes the factorization of a real symmetric or complex Hermitian positive-definite matrix A. The factorization has the form:

   A = L *  L**T in case of lower triangular or symmetric matrix A

or

   A = U**T  * U in case of upper triangular matrix A

where L is lower triangular, U is upper triangular. LAPACK function [POTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/potrf.md).

Computing for type matrix<double>

```
bool  matrix::FactorizationCholesky(
   matrix&         L             // lower or upper triangular matrix
   );
```

Computing for type matrix<float>

```
bool  matrix::FactorizationCholesky(
   matrixf&        L             // lower or upper triangular matrix
   );
```

Computing for type matrix<complex>

```
bool  matrix::FactorizationCholesky(
   matrixc&        L             // lower or upper triangular matrix
   );
```

Computing for type matrix<complexf>

```
bool  matrix::FactorizationCholesky(
   matrixcf&       L             // lower or upper triangular matrix
   );
```

Parameters

L

[out]  Lower or upper triangular matrix.

 

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

The input can be a symmetric (Hermitian), [upper triangular](matrix_triu.md) or [lower triangular](matrix_tril.md) matrix. Triangular matrices are assumed to be symmetric (Hermitian conjugated).

Matrices L and D can be used for further calculations with methods [LDLSyTridPDLinearEquationsSolution](ldlsytridpdlinearequations.md) and [LDLSyTridPDCondNumReciprocal](ldlsytridpdcondnumreciprocal.md).