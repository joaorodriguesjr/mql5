Transformations



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md) / Transformations

[![Previous](previous.png)](matrix_convolve.md) 
[![Next](next.png)](matrix_cholesky.md)

Matrix transformations

Matrix decomposition can be used in the following cases:

* as an intermediate step when solving systems of linear equations
* for matrix inversion
* when calculating determinants
* when finding eigenvalues and eigenvectors of a matrix
* when computing analytic functions of matrices
* when using the least squares method
* in the numerical solution of differential equations

Different matrix decomposition types are used depending on the problem.

| Function | Action |
| --- | --- |
| [Cholesky](matrix_cholesky.md) | Computes the Cholesky decomposition |
| [Eig](matrix_eig.md) | Computes the eigenvalues and right eigenvectors of a square matrix |
| [EigVals](matrix_eigvals.md) | Computes the eigenvalues of a general matrix |
| [LU](matrix_lu.md) | LU factorization of a matrix as the product of a lower triangular matrix and an upper triangular matrix |
| [LUP](matrix_lup.md) | LUP factorization with partial pivoting, which refers to LU decomposition with row permutations only: PA=LU |
| [QR](matrix_qr.md) | Compute the qr factorization of a matrix |
| [SVD](matrix_svd.md) | Singular Value Decomposition |