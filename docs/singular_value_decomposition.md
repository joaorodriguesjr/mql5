Singular value decomposition



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md) / Singular Value Decomposition

[![Previous](previous.png)](openblas.md) 
[![Next](next.png)](singularvaluedecompositiondc.md)

Singular value decomposition

This section features functions for decomposing a matrix into three components: orthogonal matrices and a diagonal matrix of singular values. SVD is applied to solve various linear algebra problems such as data dimensionality reduction, image compression, solving systems of equations, and data analysis and optimization. The main functions allow you to compute singular values and vectors, reconstruct matrices, and approximate matrices with reduced rank accuracy.

| Function | Action |
| --- | --- |
| [SingularValueDecompositionDC](singularvaluedecompositiondc.md) | Singular Value Decomposition, "divide-and-conquer" algorithm. This algorithm is considered the fastest among other SVD algorithms (LAPACK function [GESDD](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gesdd.md)). |
| [SingularValueDecompositionQR](singularvaluedecompositionqr.md) | Singular Value Decomposition, QR algorithm. This algorithm is considered a classical SVD algorithm (LAPACK function [GESVD](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gesvd.md)). |
| [SingularValueDecompositionQRPivot](singularvaluedecompositionqrp.md) | Singular Value Decomposition, QR with pivoting algorithm (LAPACK function [GESVDQ](https://docs.amd.com/r/en-US/63860-AOCL-LAPACK/SVD-Computational-Routines-APIs?section=gesvdq)). |
| [SingularValueDecompositionBisect](singularvaluedecompositionbise.md) | Singular Value Decomposition, bisection algorithm (LAPACK function [GESVDX](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gesvdx.md)). |
| [SingularValueDecompositionJacobiHigh](singularvaluedecompositionjh.md) | Singular Value Decomposition, Jacobi high level algorithm (LAPACK function [GEJSV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gejsv.md)). |
| [SingularValueDecompositionJacobiLow](singularvaluedecompositionjl.md) | Singular Value Decomposition, Jacobi low level algorithm (LAPACK function [GESVJ](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gesvj.md)). The method computes small singular values and their singular vectors with much greater accuracy than other SVD routines in certain cases. |
| [SingularValueDecompositionBidiagDC](singularvaluedecompositiondddc.md) | Singular Value Decomposition, divide-and-conquer algorithm for bidiagonal matrices (LAPACK function [BDSDC](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/bdsdc.md)). |
| [SingularValueDecompositionBidiagBisect](singularvaluedecompositionbdbs.md) | Singular Value Decomposition, bisection algorithm for bidiagonal matrices (LAPACK function [BDSVDX](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/bdsvdx.md)). |
| [SingularValueDecompositionBidiagQR](singularvaluedecompositionbdqr.md) | Computes the singular value decomposition of a general matrix that has been reduced to bidiagonal form by the method [ReduceToBidiagonal](reducetobidiagonal.md). LAPACK function [BDSQR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-0/bdsqr.md). |