Tridiagonal Matrices



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Eigen Values](eigen_values.md) / Tridiagonal Matrices

[![Previous](previous.png)](eigensymmetric2bisect.md) 
[![Next](next.png)](eigentridiagdc.md)

Tridiagonal Matrices

 

Functions for computing eigenvalues and eigenvectors of symmetric tridiagonal matrices using various algorithms. Each function implements a specific solution method and supports matrix types [double](double.md) and [float](double.md).

Common Parameters:

* jobv Determines whether to compute eigenvectors (EIGVALUES\_V) or only eigenvalues (EIGVALUES\_N).
* range Specifies the range of computed eigenvalues (BLASRANGE\_A, BLASRANGE\_V, BLASRANGE\_I).
* lower and upper Lower and upper bounds for computing a subset of the spectrum.
* abstol Absolute error tolerance.

All functions operate on symmetric tridiagonal matrices and allow selecting the most suitable algorithm depending on performance and accuracy requirements.

| Function | Action |
| --- | --- |
| [EigenTridiagonalDC](eigentridiagdc.md) | Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the divide-and-conquer algorithm (LAPACK function [STEVD](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/stevd.md)). |
| [EigenTridiagonalQR](eigentridiagqr.md) | Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the QR algorithm (LAPACK function [STEV](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/stev.md)). |
| [EigenTridiagonalRobust](eigentridiagrobust.md) | Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the Multiple Relatively Robust Representations, MRRR algorithm (LAPACK function [STEVR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/stevr.md)). |
| [EigenTridiagonalBisect](eigentridiagbisect.md) | Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the bisection algorithm (LAPACK function [STEVX](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/stevx.md)). |
| [EigenTridiagonalQL](eigentridiagql.md) | Compute all eigenvalues of a symmetric tridiagonal matrix using the Pal-Walker-Kahan variant of the QL or QR algorithm (LAPACK function [STERF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sterf.md)). |
| [EigenTridiagonalDCQ](eigentridiagdcq.md) | Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the divide-and-conquer algorithm (LAPACK function [STEDC](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/stedc.md)). |
| [EigenTridiagonalQRQ](eigentridiagqrq.md) | Compute eigenvalues and eigenvectors of a symmetric tridiagonal matrix using the QR algorithm (LAPACK function [STEQR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/steqr.md)). |
| [EigenTridiagonalPosDefQ](eigentridiagposdefq.md) | Compute eigenvalues and eigenvectors of a symmetric positive definite (положительно определённая) tridiagonal matrix using the QR algorithm (LAPACK function [PTEQR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/pteqr.md)). |