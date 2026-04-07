EigenHessenbergSchurQ



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Eigen Values](eigen_values.md)  /  [General Matrices](general_matrices.md) / EigenHessenbergSchurQ

[![Previous](previous.png)](eigensolver2schurblocked.md) 
[![Next](next.png)](eigenvectorstriangularz.md)

EigenHessenbergSchurQ

Computes the eigenvalues of a Hessenberg matrix H and the matrices T and Z from the Schur decomposition H = Z T Z**T, where T is an upper quasi-triangular matrix (the Schur form), and Z is the orthogonal matrix of Schur vectors. Optionally Z may be postmultiplied into an input orthogonal matrix Q so that this routine can give the Schur factorization of a matrix A which has been reduced to the Hessenberg form H by the orthogonal matrix Q:

    A = Q*H*Q**T = (QZ)*T*(QZ)**T.

LAPACK function [HSEQR](https://www.intel.com/content/www/us/en/docs/onemkl/developer-reference-fortran/2025-2/hseqr.md). See also [Schur decomposition](https://en.wikipedia.org/wiki/Schur_decomposition).

Computing for type matrix<double>

```
bool  matrix::EigenHessenbergSchurQ(
   matrix&               Q,                       // orthogonal matrix Q
   vectorc&              eigen_values,            // vector of computed eigenvalues
   matrix&               schur_t,                 // matrix T in Schur form
   matrix&               schur_z                  // matrix Z of Schur vectors
   );
```

Computing for type matrix<float>

```
bool  matrixf::EigenHessenbergSchurQ(
   matrixf&              Q,                       // orthogonal matrix Q
   vectorcf&             eigen_values,            // vector of computed eigenvalues
   matrixf&              schur_t,                 // matrix T in Schur form
   matrixf&              schur_z                  // matrix Z of Schur vectors
   );
```

Computing for type matrix<complex>

```
bool  matrixc::EigenHessenbergSchurQ(
   matrixc&              Q,                       // orthogonal matrix Q
   vectorc&              eigen_values,            // vector of computed eigenvalues
   matrixc&              schur_t,                 // matrix T in Schur form
   matrixc&              schur_z                  // matrix Z of Schur vectors
   );
```

Computing for type matrix<complexf>

```
bool  matrixcf::EigenHessenbergSchurQ(
   matrixcf&             Q,                       // orthogonal matrix Q
   vectorcf&             eigen_values,            // vector of computed eigenvalues
   matrixcf&             schur_t,                 // matrix T in Schur form
   matrixcf&             schur_z                  // matrix Z of Schur vectors
   );
```

Parameters

Q

[in]  Orthogonal matrix Q produced by method [ReflectHessenbergToQ](reflecthessenbergtoq.md). Matrix Q can be of zero size, in this case Hessenberg matrix (not original matrix A) will be decomposed. If matrix Q is used, then calculated the original matrix A reduced to Hessenberg form (see [ReduceToHessenberg](reducetohessenberg.md)).

eigen\_values

[out] Vector of eigenvalues.

schur\_t

[out]  Upper triangular Schur matrix (Schur form for the input matrix).

schur\_z

[out]  Matrix of Schur vectors.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

Real (non-complex) matrices can have a complex solution. Therefore, the input vector of eigenvalues must be complex. In case of a complex solution, the error code is set to [4019 (ERR\_MATH\_OVERFLOW)](errorcodes.md). Otherwise, only the real parts of the complex values of the eigenvalue vector should be used.