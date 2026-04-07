Least Squares



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md) / Least Squares

[![Previous](previous.png)](sylvesterequationtriangular3.md) 
[![Next](next.png)](leastsquaressolution.md)

Least Squares

The Least Squares section provides a set of versatile functions for solving overdetermined or underdetermined linear systems of the form A * X ≈ B using least squares methods. These functions support a variety of matrix types (float, double, complex, complexf) and implement several numerically stable algorithms based on standard LAPACK routines.

Supported Methods:

* QR / LQ factorization (LeastSquaresSolution) the primary approach for solving systems with full-rank matrices.
* QR with compact WY representation (LeastSquaresSolutionWY) an efficient method optimized for block operations.
* SVD-based methods (for rank-deficient matrices):
  + LeastSquaresSolutionDC using a divide-and-conquer algorithm,
  + LeastSquaresSolutionSVD using classical singular value decomposition.* QR with column pivoting (QR with pivoting) (LeastSquaresSolutionQRPivot) provides robust solutions for rank-deficient systems and computes the effective rank.
  * Tall-Skinny QR / Short-Wide LQ (LeastSquaresSolutionQRTallSkinny) optimized for very tall or wide matrices.

 

Key Features:

* Support for solving systems in various forms: with matrix A, its transpose (At), or Hermitian conjugate (AH).
* Computation of residual vectors and singular values (for SVD-based methods).
* Estimation of the effective rank of matrix A.
* Support for both single right-hand side vectors and multiple right-hand side matrices.

| Function | Action |
| --- | --- |
| [LeastSquaresSolution](leastsquaressolution.md) | Solves overdetermined or underdetermined real / complex linear systems involving an m-by-n matrix A, or its transpose / conjugate-transpose, using a QR or LQ factorization of A. It is assumed that A has full rank. LAPACK function [GELS](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gels.md). |
| [LeastSquaresSolutionDC](leastsquaressolutiondc.md) | Computes the minimum-norm solution to a real or complex linear least squares problem: minimize 2-norm(| b - A*x |) using the singular value decomposition ([SVD](singularvaluedecompositiondc.md)) of A. A is an m-by-n matrix which may be rank-deficient. The divide and conquer algorithm makes very mild assumptions about floating point arithmetic. LAPACK function [GELSD](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gelsd.md). |
| [LeastSquaresSolutionSVD](leastsquaressolutionsvd.md) | Computes the minimum-norm solution to a real or complex linear least squares problem: minimize 2-norm(| b - A*x |) using the singular value decomposition ([SVD](singularvaluedecompositionqr.md)) of A. A is an m-by-n matrix which may be rank-deficient. LAPACK function [GELSS](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gelss.md). |
| [LeastSquaresSolutionWY](leastsquaressolutionwy.md) | Solves overdetermined or underdetermined real / complex linear systems involving an m-by-n matrix A, or its transpose / conjugate-transpose, using a QR or LQ factorization of A with compact WY representation of Q. It is assumed that A has full rank. LAPACK function [GELST](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gelst.md). |
| [LeastSquaresSolutionsQRPivot](leastsquaressolutionqrpivot.md) | Computes the minimum-norm solution to a real or complex linear least squares problem: minimize 2-norm(| b - A*x |) using a complete orthogonal factorization of A. A is an m-by-n matrix which may be rank-deficient. LAPACK function [GELSY](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gelsy.md). |
| [LeastSquaresSolutionQRTallSkinny](leastsquaressolutionqrts.md) | Solves overdetermined or underdetermined real / complex linear systems involving an m-by-n matrix A, or its transpose / conjugate-transpose, using a tall skinny QR or short wide LQ factorization of A. It is assumed that A has full rank. LAPACK function [GETSLS](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/getsls.md). |