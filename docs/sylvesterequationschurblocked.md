SylvesterEquationSchurBlocked



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Factored Calculations](factored_calculations.md) / SylvesterEquationSchurBlocked

[![Previous](previous.png)](sylvesterequationschur.md) 
[![Next](next.png)](pseudo_inverse.md)

SylvesterEquationSchurBlocked

Solves Sylvester equation for real quasi-triangular or complex triangular matrices:

   A*X + X*B = C

where  A and B are both upper triangular. A is m-by-m and B is n-by-n; the right hand side C and the solution X are m-by-n.

A and B must be in Schur canonical form (as returned by [EigenHessenbergSchurQ](eigenhessenbergschurq.md) or [EigenSolverSchur](eigensolverschur.md)), that is, in case of real quasi-triangular, block upper triangular with 1-by-1 and 2-by-2 diagonal blocks; each 2-by-2 diagonal block has its diagonal elements equal and its off-diagonal elements of opposite sign.

LAPACK function [TRSYL3](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trsyl3.md). This is the block (BLAS level 3) version of [TRSYL](sylvesterequationtriangular.md). Faster up to 5 times but not so accurate.

Computing for type matrix<double>

```
bool  matrix::SylvesterEquationSchurBlocked(
   matrix&              B,            // matrix B in Schur form
   matrix&              QA,           // orthogonal matrix of Schur vectors of the input matrix A
   matrix&              QB,           // orthogonal matrix of Schur vectors of the matrix B
   matrix&              C,            // right hand side matrix C
   matrix&              X             // solution matrix X
   );
```

Computing for type matrix<float>

```
bool  matrixf::SylvesterEquationSchurBlocked(
   matrixf&             B,            // matrix B in Schur form
   matrixf&             QA,           // orthogonal matrix of Schur vectors of the input matrix A
   matrixf&             QB,           // orthogonal matrix of Schur vectors of the matrix B
   matrixf&             C,            // right hand side matrix C
   matrixf&             X             // solution matrix X
   );
```

Computing for type matrix<complex>

```
bool  matrix::SylvesterEquationSchurBlocked(
   matrixc&             B,            // matrix B in Schur form
   matrixc&             QA,           // orthogonal matrix of Schur vectors of the input matrix A
   matrixc&             QB,           // orthogonal matrix of Schur vectors of the matrix B
   matrixc&             C,            // right hand side matrix C
   matrixc&             X             // solution matrix X
   );
```

Computing for type matrix<complexf>

```
bool  matrix::SylvesterEquationSchurBlocked(
   matrixcf&            B,            // matrix B in Schur form
   matrixcf&            QA,           // orthogonal matrix of Schur vectors of the input matrix A
   matrixcf&            QB,           // orthogonal matrix of Schur vectors of the matrix B
   matrixcf&            C,            // right hand side matrix C
   matrixcf&            X             // solution matrix X
   );
```

Parameters

B

[in]  Real quasi-triangular or complex triangular matrix B in Schur form (output parameter schur\_matrix in [EigenSolverSchur](eigensolverschur.md) or schur\_t in [EigenHessenbergSchurQ](eigenhessenbergschurq.md))

QA

[in]  Real orthogonal or complex unitary matrix of Schur vectors of the original matrix A (output parameter schur\_vectors in [EigenSolverSchur](eigensolverschur.md) or schur\_z in [EigenHessenbergSchurQ](eigenhessenbergschurq.md))

QB

[in]  Real orthogonal or complex unitary matrix of Schur vectors of the original matrix A (output parameter schur\_vectors in [EigenSolverSchur](eigensolverschur.md) or schur\_z in [EigenHessenbergSchurQ](eigenhessenbergschurq.md))

C

[in]  Matrix C whose columns are the right-hand sides for the systems of equations.

X

[out]  Matrix X with solution of Sylvester equation.

 

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

Output matrix X has the same sizes as input matrix C.

Функция [TRSYL3](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trsyl3.md) обрабатывает только верхнетреугольные матрицы A и B. Для того, чтобы вычислить уравнение Сильвестра для любых квадратных матриц, необходимо предварительно использовать разложение Шура. Например, имеем 2 обычные матрицы A и B, тогда получаем две пары матриц разложения Шура:

A.EigenSolverShur(EIGSCHUR\_V,EV,SA,QA);

B.EigenSolverShur(EIGSCHUR\_V,EV,SB,QB);

и решаем уравнение Сильвестра:

SA.SylvesterEquationSchurBlocked(SB,QA,QB,C,X);