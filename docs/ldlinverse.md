LDLInverse



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Factored Calculations](factored_calculations.md) / LDLInverse

[![Previous](previous.png)](ldllinearequationssolution.md) 
[![Next](next.png)](ldlcondnumreciprocal.md)

LDLInverse

Computes the inverse of a real symmetric or complex Hermitian indefinite matrix using the factorization A = U**T * D * U or A = L * D * L**T computed by [FactorizationLDLRaw](factorizationldlraw.md). LAPACK functions [SYTRI](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytri.md), [HETRI](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hetri.md).

Computing for type matrix<double>

```
bool  matrix::LDLInverse(
   long[]&         ipiv,          // pivot indices array
   matrix&         AI             // inverse of matrix A
   );
```

Computing for type matrix<float>

```
bool  matrixf::LDLInverse(
   long[]&         ipiv,          // pivot indices array
   matrixf&        AI             // inverse of matrix A
   );
```

Computing for type matrix<complex>

```
bool  matrixc::LDLInverse(
   long[]&         ipiv,          // pivot indices array
   matrixc&        AI             // inverse of matrix A
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::LDLInverse(
   long[]&         ipiv,          // pivot indices array
   matrixcf&       AI             // inverse of matrix A
   );
```

Parameters

ipiv

[in]  Pivot indices array obtained as result of SYTRF or HETRF function.

AI

[out]  Inverted matrix.

 

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

This method is applied to the matrix AF obtained as result of SYTRF or HETRF function.