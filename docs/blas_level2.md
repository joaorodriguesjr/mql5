BLAS Level 2



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md) / BLAS Level 2

[![Previous](previous.png)](eigenhessenbergbalancedschurq.md) 
[![Next](next.png)](blasl2gemv.md)

BLAS Level 2

The BLAS Level 2 section describes functions for performing operations between matrices and vectors that implement second-level linear algebra computations matrixvector multiplication, linear combinations, and rank updates of matrices. These functions implement the standard procedures of the BLAS (Level 2) library and provide efficient computation for real, complex, and Hermitian matrices.

BLAS Level 2 functions are designed for:

* computing matrixvector products;
* updating matrices (rank-1 and rank-2 modifications);
* working with specific matrix types symmetric, Hermitian, and triangular;
* performing computations with support for different data types: float, double, complexf, and complex.

All functions return true if successful and false in case of an error.

| Function | Action |
| --- | --- |
| [BlasL2GeMV](blasl2gemv.md) | Computes a matrix-vector product using a general m-by-n matrix. y = alpha * op(A) * x + beta * y. BLAS function [GEMV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gemv.md). |
| [BlasL2SyMV](blasl2symv.md) | Computes a matrix-vector product for a symmetric n-by-n matrix. y = alpha*A*x + beta*y. BLAS function [SYMV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/symv-002.md). |
| [BlasL2HeMV](blasl2hemv.md) | Computes a matrix-vector product for a Hermitian n-by-n matrix. y = alpha*A*x + beta*y. BLAS function [HEMV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hemv.md). |
| [BlasL2TrMV](blasl2trmv.md) | Computes a matrix-vector product using a triangular n-by-n matrix. y = op(A) * x. BLAS function [TRMV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trmv.md). |
| [BlasL2GeR](blasl2ger.md) | Performs a rank-1 update of a general m-by-n matrix. AU = alpha*x*y + A. BLAS functions [GER](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/ger.md), [GERU](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/geru.md). |
| [BlasL2GeRC](blasl2gerc.md) | Performs a rank-1 conjugated update of a general m-by-n matrix. AU = alpha * x * conjg(y) + A. BLAS function [GERC](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gerc.md). |
| [BlasL2SyR](blasl2syr.md) | Performs a rank-1 update of a symmetric n-by-n matrix. AU = alpha*x*x + A. BLAS function [SYR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/syr-001.md). |
| [BlasL2HeR](blasl2her.md) | Performs a rank-1 conjugated update of a Hermitian n-by-n matrix. AU = alpha * x * conjg(x) + A. BLAS function [HER2](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/her2.md). |
| [BlasL2SyR2](blasl2syr2.md) | Performs a rank-2 update of a symmetric n-by-n matrix. AU = alpha*x*y + alpha*y*x + A. BLAS function [SYR2](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/syr2.md). |
| [BlasL2HeR2](blasl2her2.md) | Performs a rank-2 conjugated update of a Hermitian n-by-n matrix. AU = alpha * x * conjg(y) + conjg(alpha) * y * conjg(x) + A. BLAS function [HER2](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/her2.md). |

Main Function Groups

1. General Matrices

* [BlasL2GeMV](blasl2gemv.md) computes a matrixvector product: y = α·op(A)·x + β·y (BLAS GEMV)
* [BlasL2GeR](blasl2ger.md) performs a rank-1 matrix update: A ← A + α·x·yᵀ (BLAS GER, GERU)
* [BlasL2GeRC](blasl2gerc.md) complex variant with conjugation: A ← A + α·x·conjg(yᵀ) (BLAS GERC)

2. Symmetric Matrices (Real)

* [BlasL2SyMV](blasl2symv.md) computes a matrixvector product for a symmetric matrix: y = α·A·x + β·y (BLAS SYMV)
* [BlasL2SyR](blasl2syr.md) performs a rank-1 update of a symmetric matrix: A ← A + α·x·xᵀ (BLAS SYR)
* [BlasL2SyR2](blasl2syr2.md) performs a rank-2 update: A ← A + α·(x·yᵀ + y·xᵀ) (BLAS SYR2)

3. Hermitian Matrices (Complex)

* [BlasL2HeMV](blasl2hemv.md) computes a matrixvector product for a Hermitian matrix: y = α·A·x + β·y (BLAS HEMV)
* [BlasL2HeR](blasl2her.md) performs a rank-1 Hermitian matrix update: A ← A + α·x·conjg(xᵀ) (BLAS HER)
* [BlasL2HeR2](blasl2her2.md) performs a rank-2 Hermitian update: A ← A + α·x·conjg(yᵀ) + conjg(α)·y·conjg(xᵀ) (BLAS HER2)

4. Triangular Matrices

* [BlasL2TrMV](blasl2trmv.md) computes a matrixvector product using a triangular matrix: y = op(A)·x, where op(A) is A, Aᵀ, or Aᴴ depending on the parameter (BLAS TRMV)