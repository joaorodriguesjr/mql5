FactorizationLDLRaw



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Factorizations](factorizations.md) / FactorizationLDLRaw

[![Previous](previous.png)](factorizationplugetridraw.md) 
[![Next](next.png)](factorizationldlcomplexsyraw.md)

FactorizationLDLRaw

Computes the factorization of a real symmetric or complex Hermitian matrix A using the Bunch-Kaufman diagonal pivoting method. The form of the factorization is:

   A = L * D * L**T in case of lower triangular or symmetric matrix A

or

   A = U**T * D * U in case of upper triangular matrix A

where L is lower triangular with unit diagonal elements, U is upper triangular with unit diagonal elements. D is a symmetric block-diagonal matrix with 1-by-1 and 2-by-2 diagonal blocks. LAPACK functions [SYTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytrf.md), [HETRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hetrf.md).

Computing for type matrix<double>

```
bool  matrix::FactorizationLDLRaw(
   matrix&         AF,           // factored matrix A
   long[]&         ipiv          // pivot indices array
   );
```

Computing for type matrix<float>

```
bool  matrixf::FactorizationLDLRaw(
   matrixf&        AF,           // factored matrix A
   long[]&         ipiv          // pivot indices array
   );
```

Computing for type matrix<complex>

```
bool  matrixc::FactorizationLDLRaw(
   matrixc&        AF,           // factored matrix A
   long[]&         ipiv          // pivot indices array
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::FactorizationLDLRaw(
   matrixcf&       AF,           // factored matrix A
   long[]&         ipiv          // pivot indices array
   );
```

Parameters

AF

[out]  Factored matrix A. The block diagonal matrix D and factor L or U.

ipiv

[out]  Pivot indices array of size N; details of the interchanges and the block structure of D.

 

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

The input can be a symmetric (Hermitian), [upper triangular](matrix_triu.md) or [lower triangular](matrix_tril.md) matrix. Triangular matrices are assumed to be symmetric (Hermitian conjugated).

Matrix AF and pivot indices array ipiv[] are raw output of the SYTRF (HETRF) function and can be used for further calculations with methods [LDLLinearEquationsSolution](ldllinearequationssolution.md), [LDLInverse](ldlinverse.md) and [LDLCondNumReciprocal](ldlcondnumreciprocal.md).