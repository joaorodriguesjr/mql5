General Matrices



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Eigen Values](eigen_values.md) / General Matrices

[![Previous](previous.png)](eigen_values.md) 
[![Next](next.png)](eigensolver.md)

General Matrices

Functions for calculating eigenvalues and eigenvectors of a square matrix using classical algorithms. It provides various methods for working with both real and complex matrices, allowing you to solve linear algebra problems with a choice of methods for calculating eigenvectors.

| Function | Action |
| --- | --- |
| [EigenSolver](eigensolver.md) | Compute eigenvalues and eigenvectors of a regular square matrix using the classical algorithm (LAPACK function [GEEV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/geev.md)). |
| [EigenSolverX](eigensolverx.md) | Compute eigenvalues and eigenvectors of a regular square matrix in Expert mode, i.e. with the ability to influence the computation algorithm and the ability to obtain accompanying computation data (LAPACK function [GEEVX](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/geevx.md)). |
| [EigenSolverSchur](eigensolverschur.md) | Compute eigenvalues, upper triangular matrix in Schur form, and matrix of Schur vectors (LAPACK function [GEES](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gees.md)). See also [Schur decomposition](https://en.wikipedia.org/wiki/Schur_decomposition). |
| [EigenSolver2](eigensolver2.md) | Compute generalized eigenvalues and eigenvectors for a pair of ordinary square matrices (LAPACK function [GGEV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/ggev.md)). |
| [EigenSolver2X](eigensolver2x.md) | Compute generalized eigenvalues and eigenvectors for a pair of regular square matrices in Expert mode, i.e. with the ability to influence the computation algorithm and the ability to obtain accompanying computation data (LAPACK function [GGEVX](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/ggevx.md)). Both matrices must be the same size. |
| [EigenSolver2Schur](eigensolver2schur.md) | Compute a pair of ordinary square matrices of generalized eigenvalues,  generalized eigenvectors, generalized Schur forms, as well as left and right Schur vectors (LAPACK function [GGES](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gges.md)). |
| [EigenSolver2Blocked](eigensolver2blocked.md) | Compute generalized eigenvalues and eigenvectors for a pair of regular square matrices using a block algorithm (LAPACK function [GGEV3](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/ggev3.md)). Both matrices must be the same size. The method parameters are exactly the same as [EigenSolver2](eigensolver2.md). |
| [EigenSolver2SchurBlocked](eigensolver2schurblocked.md) | Compute a pair of regular square matrices of generalized eigenvalues,  generalized eigenvectors, generalized Schur forms, as well as left and right Schur vectors (LAPACK function [GGES3](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gges3.md)). |
| [EigenHessenbergSchurQ](eigenhessenbergschurq.md) | Computes the eigenvalues of a Hessenberg matrix H and the matrices T and Z from the Schur decomposition H = Z T Z**T, where T is an upper quasi-triangular matrix (the Schur form), and Z is the orthogonal matrix of Schur vectors. LAPACK function [HSEQR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hseqr.md). See also [Schur decomposition](https://en.wikipedia.org/wiki/Schur_decomposition). |
| [EigenVectorsTriangularZ](eigenvectorstriangularz.md) | Computes eigenvectors of an real upper quasi-triangular or complex upper triangular matrix computed by [EigenHessenbergSchurQ](eigenhessenbergschurq.md) or [EigenSolverSchur](eigensolverschur.md). A = Q * T * Q**H, where T is an upper quasi-triangular matrix (the Schur form), and Q is the orthogonal matrix of Schur vectors. LAPACK function [TREVC](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trevc.md). |
| [EigenVectorsTriangularZBlocked](eigenvectorstriangularzblocked.md) | Computes eigenvectors of an real upper quasi-triangular or complex upper triangular matrix computed by [EigenHessenbergSchurQ](eigenhessenbergschurq.md) or [EigenSolverSchur](eigensolverschur.md). A = Q * T * Q**H, where T is an upper quasi-triangular matrix (the Schur form), and Q is the orthogonal matrix of Schur vectors. LAPACK function [TREVC3](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trevc3.md). This is the block version (OpenBLAS level 3) of [TREVC](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/trevc.md). Faster but not so accurate. |