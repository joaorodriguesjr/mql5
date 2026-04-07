LDLComplexSyInverse



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Factored Calculations](factored_calculations.md) / LDLComplexSyInverse

[![Previous](previous.png)](ldlcomplexsylinearequationssolution.md) 
[![Next](next.png)](ldlcomplexsycondnumreciprocal.md)

LDLComplexSyInverse

Computes the inverse of a complex symmetric indefinite matrix using the factorization A = U**T * D * U or A = L * D * L**T computed by [FactorizationLDLComplexSyRaw](factorizationldlcomplexsyraw.md). LAPACK function [SYTRI](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytri.md).

Computing for type matrix<complex>

```
bool  matrixc::LDLComplexSyInverse(
   long[]&         ipiv,          // pivot indices array
   matrixc&        AI             // inverse of matrix A
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::LDLComplexSyInverse(
   long[]&         ipiv,          // pivot indices array
   matrixcf&       AI             // inverse of matrix A
   );
```

Parameters

ipiv

[in]  Pivot indices array obtained as result of SYTRF function.

AI

[out]  Inverted matrix.

 

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

This method is applied to the matrix AF obtained as result of SYTRF function.