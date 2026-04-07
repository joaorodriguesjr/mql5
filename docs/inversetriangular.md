InverseTriangular



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Linear Equations](linear_equations.md) / InverseTriangular

[![Previous](previous.png)](linearequationssolutiontriangl.md) 
[![Next](next.png)](condnumreciprocaltriangular.md)

InverseTriangular

Computes the inverse of a upper or lower triangular matrix A. LAPACK function [TRTRI](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trtri.md).

Computing for type matrix<double>

```
bool  matrix::InverseTriangular(
   matrix&         AI             // inverse of matrix A
   );
```

Computing for type matrix<float>

```
bool  matrixf::InverseTriangular(
   matrixf&        AI             // inverse of matrix A
   );
```

Computing for type matrix<complex>

```
bool  matrixc::InverseTriangular(
   matrixc&        AI             // inverse of matrix A
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::InverseTriangular(
   matrixcf&       AI             // inverse of matrix A
   );
```

Parameters

AI

[out]  Inverted matrix.

 

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).