Factorizations



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md) / Factorizations

[![Previous](previous.png)](factorizationrq.md) 
[![Next](next.png)](factorizationplu.md)

Factorizations

The Factorizations section contains functions for performing various types of matrix factorizations used in numerical solutions of linear systems, stability analysis, and other linear algebra tasks. These factorizations transform the original matrix into simpler forms, making subsequent computations more efficient. All functions are implemented using LAPACK routines and support the types [double](double.md), float, [complex](complex.md), and complexf.

The functions in this section are used for:

* Preprocessing matrices when solving systems of linear equations;
* Computing determinants, ranks, and matrix inverses;
* Assessing the stability of numerical methods;
* Solving problems in spectral theory and optimization methods.

Matrix factorization is a critical step in many linear algebra algorithms, and this section provides access to the most efficient and well-established factorization techniques.

| Function | Action |
| --- | --- |
| [FactorizationPLU](factorizationplu.md) | Computes an LU factorization of a general M-by-N matrix A using partial pivoting with row interchanges. The factorization has the form A = P * L * U. LAPACK function [GETRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/getrf.md). |
| [FactorizationPLUQ](factorizationpluq.md) | Computes an LU factorization of a general N-by-N matrix A with complete pivoting (row and column interchanges). The factorization has the form A = P * L * U * Q where P is a rows permutation matrix, L is lower triangular with unit diagonal elements, U is upper triangular, and Q is a columns permutation matrix. LAPACK function [GETC2](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/getc2.md). |
| [FactorizationPLUGeTrid](factorizationplugetrid.md) | Computes an LU factorization of a general (non-symmetric) tridiagonal N-by-N matrix A using elimination with partial pivoting and row interchanges. The factorization has the form A = P * L * U. LAPACK function [GTTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gttrf.md). |
| [FactorizationLDL](factorizationldl.md) | Computes the factorization of a real symmetric or complex Hermitian matrix A using the Bunch-Kaufman diagonal pivoting method. LAPACK functions [SYTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytrf.md), [HETRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hetrf.md). |
| [FactorizationLDLComplexSy](factorizationldlcomplexsy.md) | Computes the factorization of a complex symmetric (not Hermitian conjugated!) matrix A using the Bunch-Kaufman diagonal pivoting method. LAPACK function [SYTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytrf.md). |
| [FactorizationLDLSyTridPD](factorizationldlsytridpd.md) | Forms the factorization of a symmetric positive-definite or, for complex data, Hermitian positive-definite tridiagonal matrix A. LAPACK function [PTTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/pttrf.md). |
| [FactorizationCholesky](factorizationcholesky.md) | Computes the factorization of a real symmetric or complex Hermitian positive-definite matrix A.  LAPACK function [POTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/potrf.md). |
| [FactorizationCholeskySyPS](factorizationcholeskysyps.md) | Computes the Cholesky factorization with complete pivoting of a real symmetric (complex Hermitian) positive semidefinite N-by-N matrix. LAPACK function [PSTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/pstrf.md). |
| [FactorizationPLURaw](factorizationpluraw.md) | Computes an LU factorization of a general M-by-N matrix A using partial pivoting with row interchanges. The factorization has the form A = P * L * U where P is a permutation matrix, L is lower triangular with unit diagonal elements (lower trapezoidal if m > n), and U is upper triangular (upper trapezoidal if m < n). LAPACK function [GETRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/getrf.md). |
| [FactorizationPLUQRaw](factorizationpluqraw.md) | Computes an LU factorization of a general N-by-N matrix A with complete pivoting (row and column interchanges). The factorization has the form A = P * L * U * Q where P is a rows permutation matrix, L is lower triangular with unit diagonal elements, U is upper triangular, and Q is a columns permutation matrix. LAPACK function [GETC2](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/getc2.md). |
| [FactorizationPLUGeTridRaw](factorizationplugetridraw.md) | Computes an LU factorization of a general (non-symmetric) tridiagonal N-by-N matrix A using elimination with partial pivoting and row interchanges. The factorization has the form A = P * L * U where P is a permutation matrix, L is lower triangular with unit diagonal elements, and U is upper triangular. LAPACK function [GTTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/gttrf.md). |
| [FactorizationLDLRaw](factorizationldlraw.md) | Computes the factorization of a real symmetric or complex Hermitian matrix A using the Bunch-Kaufman diagonal pivoting method. LAPACK functions [SYTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytrf.md), [HETRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hetrf.md). |
| [FactorizationLDLComplexSyRaw](factorizationldlcomplexsyraw.md) | Computes the factorization of a complex symmetric matrix A using the Bunch-Kaufman diagonal pivoting method. LAPACK function [SYTRF](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/sytrf.md). |