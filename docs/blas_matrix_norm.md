Matrix Norm



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md) / Matrix Norm

[![Previous](previous.png)](reflecthessenbergtoq.md) 
[![Next](next.png)](matrixnormge.md)

Matrix Norm

 

This section presents functions for computing various matrix norms for different matrix structuresgeneral (rectangular), tridiagonal, upper Hessenberg, symmetric/Hermitian (both full and tridiagonal), and triangular/trapezoidal. Each routine is templated for four data types (double, float, std::complex<double>, std::complex<float>) and overloads the signature

```
bool MatrixNorm*(ENUM_BLAS_NORMX norm, T& norm_value);
```

where norm specifies one of:

* 1‑norm (BLASNORMX\_O)
* Infinity‑norm (BLASNORMX\_I)
* Frobenius norm (BLASNORMX\_F)
* max‑abs element (BLASNORMX\_M)

Results are returned via norm\_value; the function returns true on success or false on error.

Under the hood, all routines call optimized LAPACK driversLANGE, LANGT, LANHS, LANSY/LANHE, LANST/LANHT, and LANTRto guarantee both high performance and numerical reliability in large‑scale linear‑algebra computations.

| Function | Action |
| --- | --- |
| [MatrixNorm](matrixnormge.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of a general rectangular matrix. LAPACK function [LANGE](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/lange.md). |
| [MatrixNormGeTrid](matrixnormgetrid.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of a general tridiagonal matrix. LAPACK function [LANGT](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/langt.md). |
| [MatrixNormHessenberg](matrixnormhessenberg.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of an upper Hessenberg matrix. LAPACK function [LANHS](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/lanhs.md). |
| [MatrixNormSy](matrixnormsy.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of a real symmetric or complex Hermitian matrix. LAPACK functions [LANSY](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/lansy.md), [LANHE](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/lanhe.md). |
| [MatrixNormComplexSy](matrixnormcomplexsy.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of a complex symmetric (not Hermitian) matrix. LAPACK function [LANSY](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/lansy.md). |
| [MatrixNormSyTrid](matrixnormsytrid.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of a real symmetric or complex Hermitian tridiagonal matrix. LAPACK functions [LANST](https://docs.amd.com/r/en-US/63860-AOCL-LAPACK/Matrix-Norm-APIs?section=lanst), [LANHT](https://docs.amd.com/r/en-US/63860-AOCL-LAPACK/Matrix-Norm-APIs?section=lanht). |
| [MatrixNormTriangular](matrixnormtriangular.md) | Returns the value of the 1-norm, infinity-norm, Frobenius norm, or the largest absolute value of any element of a trapezoidal m-by-n or triangular matrix. LAPACK function [LANTR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/lantr.md). |