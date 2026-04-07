SingularValueDecompositionQRPivot



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Singular Value Decomposition](singular_value_decomposition.md) / SingularValueDecompositionQRPivot

[![Previous](previous.png)](singularvaluedecompositionqr.md) 
[![Next](next.png)](singularvaluedecompositionbise.md)

SingularValueDecompositionQRPivot

Singular Value Decomposition, QR with pivoting algorithm (LAPACK function [GESVDQ](https://docs.amd.com/r/en-US/63860-AOCL-LAPACK/SVD-Computational-Routines-APIs?section=gesvdq)).

Computing for type matrix<double>

```
bool  matrix::SingularValueDecompositionQRPivot(
   ENUM_SVDQRP_A   joba,     // computation accuracy level
   ENUM_SVDQRP_P   jobp,     // use row reversal to compute
   ENUM_SVDQRP_R   jobr,     // use triangular matrix R to compute
   ENUM_SVDQRP_U   jobu,     // how to compute left vectors
   ENUM_SVDQRP_V   jobv,     // how to compute right vectors
   vector&         S,        // vector of computed singular values
   matrix&         U,        // matrix of computed left vectors U
   matrix&         VT        // transposed matrix of right vectors VT
   );
```

Computing for type matrix<float>

```
bool  matrix::SingularValueDecompositionQRPivot(
   ENUM_SVDQRP_A   joba,     // computation accuracy level
   ENUM_SVDQRP_P   jobp,     // use row reversal to compute
   ENUM_SVDQRP_R   jobr,     // use triangular matrix R to compute
   ENUM_SVDQRP_U   jobu,     // how to compute left vectors
   ENUM_SVDQRP_V   jobv,     // how to compute right vectors
   vectorf&        S,        // vector of computed singular values
   matrixf&        U,        // matrix of computed left vectors U
   matrixf&        VT        // transposed matrix of right vectors VT
   );
```

Computing for type matrix<complex>

```
bool  matrix::SingularValueDecompositionQRPivot(
   ENUM_SVDQRP_A   joba,     // computation accuracy level
   ENUM_SVDQRP_P   jobp,     // use row reversal to compute
   ENUM_SVDQRP_R   jobr,     // use triangular matrix R to compute
   ENUM_SVDQRP_U   jobu,     // how to compute left vectors
   ENUM_SVDQRP_V   jobv,     // how to compute right vectors
   vector&         S,        // vector of computed singular values
   matrixc&        U,        // matrix of computed left vectors U
   matrixc&        VT        // transposed matrix of right vectors VT
   );
```

Computing for type matrix<complexf>

```
bool  matrix::SingularValueDecompositionQRPivot(
   ENUM_SVDQRP_A   joba,                   // computation accuracy level
   ENUM_SVDQRP_P   jobp,                   // use row reversal to compute
   ENUM_SVDQRP_R   jobr,                   // use triangular matrix R to compute
   ENUM_SVDQRP_U   jobu,                   // how to compute left vectors
   ENUM_SVDQRP_V   jobv,                   // how to compute right vectors
   vectorf&        singular_values,        // vector of computed singular values
   matrixcf&       u,                      // matrix of computed left vectors U
   matrixcf&       vt                      // transposed matrix of right vectors VT
   );
```

Parameters

joba

[in] [ENUM\_SVDQRP\_A](singularvaluedecompositionqrp.md#enum_svdqrp_a) enumeration value defining the accuracy level of the SVD computation.

jobp

[in] [ENUM\_SVDQRP\_P](singularvaluedecompositionqrp.md#enum_svdqrp_a) enumeration value defining the use of row reversal during the computation process.

jobr

[in] [ENUM\_SVDQRP\_R](singularvaluedecompositionqrp.md#enum_svdqrp_r) enumeration value defining whether to transpose the triangular matrix R obtained as a result of the initial QR factorization.

jobu

[in] [ENUM\_SVDQRP\_U](singularvaluedecompositionqrp.md#enum_svdqrp_u) enumeration value that determines how the left singular vectors should be computed.

jobv

[in] [ENUM\_SVDQRP\_V](singularvaluedecompositionqrp.md#enum_svdqrp_v) enumeration value defining how the right singular vectors should be computed.

S

[out] Vector of singular values.

U

[out] Matrix of left singular vectors.

VT

[out] Matrix of right singular vectors.

Return Value

Return true if successful, otherwise false in case of an [error](errorcodes.md).

Note

The number of matrix rows must not be less than the number of columns.

If both left and right singular vectors are computed, jobv must be set to SVDQRPV\_R when jobu=SVDQRPU\_R.

 

ENUM\_SVDQRP\_A

An enumeration that specifies the level of accuracy of the SVD computation.

| ID | Description |
| --- | --- |
| SVDQRP\_A | The requested accuracy corresponds to the inverse error limited by epsilon. This is an aggressive level of truncation. |
| SVDQRPA\_M | Similar to SVDQRP\_A, but the truncation is softer. This is the average level of truncation. |
| SVDQRPA\_H | High accuracy is required. |

ENUM\_SVDQRP\_P

An enumeration that specifies whether to use row reversal during calculation.

| ID | Description |
| --- | --- |
| SVDQRPP\_P | The rows of A are ordered in descending order. Recommended for numerical reliability. |
| SVDQRPP\_N | No row reversal. |

ENUM\_SVDQRP\_R

An enumeration that specifies whether to transpose the triangular matrix R obtained as a result of the initial QR factorization.

| ID | Description |
| --- | --- |
| SVDQRPR\_T | After the initial rotated QR factorization, GESVD is applied to the transpose R**T of the calculated triangular factor R. |
| SVDQRPR\_N | The triangular factor R is given as input to GESVD. |

ENUM\_SVDQRP\_U

An enumeration defining how left singular vectors should be computed.

| ID | Description |
| --- | --- |
| SVDQRPU\_A | All M left singular vectors are computed. |
| SVDQRPU\_S | The min(M,N) left singular vectors are computed. |
| SVDQRPU\_R | The numerical rank NUMRANK is determined and only the NUMRANK of the left singular vectors is computed. |
| SVDQRPU\_F | N left singular vectors are returned. |
| SVDQRPU\_N | Left singular vectors are not computed. |

ENUM\_SVDQRP\_V

An enumeration defining how right singular vectors should be computed.

| ID | Description |
| --- | --- |
| SVDQRPV\_A | All N right singular vectors are computed. |
| SVDQRPV\_R | The numerical rank NUMRANK is defined and only the NUMRANK of right singular vectors are computed. |
| SVDQRPV\_N | Right singular vectors are not computed. |

 

See also

[SingularValueDecompositionDC](singularvaluedecompositiondc.md), [SingularValueDecompositionQR](singularvaluedecompositionqr.md)