Matrix and Vector Methods



[MQL5 Reference](index.md) / Matrix and Vector Methods

[![Previous](previous.png)](arrayfromfp8.md) 
[![Next](next.png)](matrix_types.md)

Matrices and vectors

A matrix is a two-dimensional array of double, float, or complex numbers.

A vector is a one-dimensional array of double, float, or complex numbers. The vector has no indication of whether it is vertical or horizontal. It is determined from the use context. For example, the vector operation Dot assumes that the left vector is horizontal and the right one is vertical. If the type indication is required, one-row or one-column matrices can be used. However, this is generally not necessary.

Matrices and vectors allocate memory for data dynamically. In fact, matrices and vectors are objects that have certain properties, such as the type of data they contain and dimensions. Matrix and vector properties can be obtained using methods such as vector\_a.Size(), matrix\_b.Rows(), vector\_c.Norm(), matrix\_d.Cond() and others. Any dimension can be changed.

When creating and initializing matrices, so-called static methods are used (these are like static methods of a class). For example: matrix::Eye(), matrix::Identity(), matrix::Ones(), vector::Ones(), matrix: :Zeros(), vector::Zeros(), matrix::Full(), vector::Full(), matrix::Tri().

At the moment, matrix and vector operations do not imply the use of the complex data type, as this development direction has not yet been completed.

MQL5 supports passing of matrices and vectors to DLLs. This enables the import of functions utilizing the relevant types, from external variables.

Matrices and vectors are passed to a DLL as a pointer to a buffer. For example, to pass a matrix of type float, the corresponding parameter of the function exported from the DLL must take a float-type buffer pointer.

MQL5

```
#import "mmlib.dll"
bool sgemm(uint flags, matrix<float> &C, const matrix<float> &A, const matrix<float> &B, ulong M, ulong N, ulong K, float alpha, float beta);
#import
```

C++

```
extern "C" __declspec(dllexport) bool sgemm(UINT flags, float *C, const float *A, const float *B, UINT64 M, UINT64 N, UINT64 K, float alpha, float beta)
```

In addition to buffers, you should pass matrix and vector sizes for correct processing.

All matrix and vector methods are listed below in alphabetical order.

| Function | Action | Category |
| --- | --- | --- |
| [Activation](matrix_activation.md) | Compute activation function values and write them to the passed vector/matrix | [Machine learning](matrix_machine_learning.md) |
| [ArgMax](matrix_argmax.md) | Return the index of the maximum value | [Statistics](matrix_statistics.md) |
| [ArgMin](matrix_argmin.md) | Return the index of the minimum value | [Statistics](matrix_statistics.md) |
| [ArgSort](matrix_argsort.md) | Return the sorted index | [Manipulations](matrix_manipulations.md) |
| [Assign](matrix_assign.md) | Copies a matrix, vector or array with auto cast | [Initialization](matrix_initialization.md) |
| [Average](matrix_average.md) | Compute the weighted average of matrix/vector values | [Statistics](matrix_statistics.md) |
| [Cholesky](matrix_cholesky.md) | Compute the Cholesky decomposition | [Transformations](matrix_decompositions.md) |
| [Clip](matrix_clip.md) | Limits the elements of a matrix/vector to a given range of valid values | [Manipulations](matrix_manipulations.md) |
| [Col](matrix_col.md) | Return a column vector. Write a vector to the specified column. | [Manipulations](matrix_manipulations.md) |
| [Cols](matrix_cols.md) | Return the number of columns in a matrix | [Features](matrix_characteristics.md) |
| [Compare](matrix_compare.md) | Compare the elements of two matrices/vectors with the specified precision | [Manipulations](matrix_manipulations.md) |
| [CompareByDigits](matrix_comparebydigits.md) | Compare the elements of two matrices/vectors with the significant figures precision | [Manipulations](matrix_manipulations.md) |
| [Cond](matrix_cond.md) | Compute the condition number of a matrix | [Features](matrix_characteristics.md) |
| [Convolve](matrix_convolve.md) | Return the discrete, linear convolution of two vectors | [Products](matrix_products.md) |
| [Copy](matrix_copy.md) | Return a copy of the given matrix/vector | [Manipulations](matrix_manipulations.md) |
| [Concat](matrix_concat.md) | Concatenate 2 submatrices to one matrix. Concatenate 2 vectors to one vector | [Manipulations](matrix_manipulations.md) |
| [CopyIndicatorBuffer](matrix_copyindicatorbuffer.md) | Get the data of the specified [indicator](indicators.md) buffer in the specified quantity to a [vector](matrix_vector.md) | [Initialization](matrix_initialization.md) |
| [CopyRates](matrix_copyrates.md) | Gets the historical series of the [MqlRates](mqlrates.md) structure of the specified symbol-period in the specified amount into a matrix or vector | [Initialization](matrix_initialization.md) |
| [CopyTicks](matrix_copyticks.md) | Get ticks from an [MqlTick](mqltick.md) structure into a matrix or a vector | [Initialization](matrix_initialization.md) |
| [CopyTicksRange](matrix_copyticksrange.md) | Get ticks from an [MqlTick](mqltick.md) structure into a matrix or a vector within the specified date range | [Initialization](matrix_initialization.md) |
| [CorrCoef](matrix_corrcoef.md) | Compute the Pearson correlation coefficient (linear correlation coefficient) | [Products](matrix_products.md) |
| [Correlate](matrix_correlate.md) | Compute the cross-correlation of two vectors | [Products](matrix_products.md) |
| [Cov](matrix_cov.md) | Compute the covariance matrix | [Products](matrix_products.md) |
| [CumProd](matrix_cumprod.md) | Return the cumulative product of matrix/vector elements, including those along the given axis | [Statistics](matrix_statistics.md) |
| [CumSum](matrix_cumsum.md) | Return the cumulative sum of matrix/vector elements, including those along the given axis | [Statistics](matrix_statistics.md) |
| [Derivative](matrix_derivative.md) | Compute activation function derivative values and write them to the passed vector/matrix | [Machine learning](matrix_machine_learning.md) |
| [Det](matrix_det.md) | Compute the determinant of a square invertible matrix | [Features](matrix_characteristics.md) |
| [Diag](matrix_diag.md) | Extract a diagonal or construct a diagonal matrix | [Manipulations](matrix_manipulations.md) |
| [Dot](matrix_dot.md) | Dot product of two vectors | [Products](matrix_products.md) |
| [Eig](matrix_eig.md) | Computes the eigenvalues and right eigenvectors of a square matrix | [Transformations](matrix_decompositions.md) |
| [EigVals](matrix_eigvals.md) | Computes the eigenvalues of a general matrix | [Transformations](matrix_decompositions.md) |
| [Eye](matrix_eye.md) | Return a matrix with ones on the diagonal and zeros elsewhere | [Initialization](matrix_initialization.md) |
| [Fill](matrix_fill.md) | Fill an existing matrix or vector with the specified value | [Initialization](matrix_initialization.md) |
| [Flat](matrix_flat.md) | Access a matrix element through one index instead of two | [Manipulations](matrix_manipulations.md) |
| [Full](matrix_full.md) | Create and return a new matrix filled with the given value | [Initialization](matrix_initialization.md) |
| [GeMM](matrix_gemm.md) | The GeMM (General Matrix Multiply) method implements the general multiplication of two matrices | [Products](matrix_products.md) |
| [HasNan](matrix_hasnan.md) | Return the number of [NaN](double.md) values in a matrix/vector | [Manipulations](matrix_manipulations.md) |
| [Hsplit](matrix_hsplit.md) | Split a matrix horizontally into multiple submatrices. Same as Split with axis=0 | [Manipulations](matrix_manipulations.md) |
| [Identity](matrix_identity.md) | Create an identity matrix of the specified size | [Initialization](matrix_initialization.md) |
| [Init](matrix_init.md) | Matrix or vector initialization | [Initialization](matrix_initialization.md) |
| [Inner](matrix_inner.md) | Inner product of two matrices | [Products](matrix_products.md) |
| [Inv](matrix_inv.md) | Compute the multiplicative inverse of a square invertible matrix by the Jordan-Gauss method | [Solutions](matrix_solves.md) |
| [Kron](matrix_kron.md) | Return Kronecker product of two matrices, matrix and vector, vector and matrix or two vectors | [Products](matrix_products.md) |
| [Loss](matrix_loss.md) | Compute loss function values and write them to the passed vector/matrix | [Machine learning](matrix_machine_learning.md) |
| [LstSq](matrix_lstsq.md) | Return the least-squares solution of linear algebraic equations (for non-square or degenerate matrices) | [Solutions](matrix_solves.md) |
| [LU](matrix_lu.md) | Implement an LU decomposition of a matrix: the product of a lower triangular matrix and an upper triangular matrix | [Transformations](matrix_decompositions.md) |
| [LUP](matrix_lup.md) | Implement an LUP factorization with partial permutation, which refers to LU decomposition with row permutations only: PA=LU | [Transformations](matrix_decompositions.md) |
| [MatMul](matrix_matmul.md) | Matrix product of two matrices | [Products](matrix_products.md) |
| [Max](matrix_max.md) | Return the maximum value in a matrix/vector | [Statistics](matrix_statistics.md) |
| [Mean](matrix_mean.md) | Compute the arithmetic mean of element values | [Statistics](matrix_statistics.md) |
| [Median](matrix_median.md) | Compute the median of the matrix/vector elements | [Statistics](matrix_statistics.md) |
| [Min](matrix_min.md) | Return the minimum value in a matrix/vector | [Statistics](matrix_statistics.md) |
| [Norm](matrix_norm.md) | Return matrix or vector norm | [Features](matrix_characteristics.md) |
| [Ones](matrix_ones.md) | Create and return a new matrix filled with ones | [Initialization](matrix_initialization.md) |
| [Outer](matrix_outer.md) | Compute the outer product of two matrices or two vectors | [Products](matrix_products.md) |
| [Percentile](matrix_percentile.md) | Return the specified percentile of values of matrix/vector elements or elements along the specified axis | [Statistics](matrix_statistics.md) |
| [PInv](matrix_pinv.md) | Compute the pseudo-inverse of a matrix by the Moore-Penrose method | [Solutions](matrix_solves.md) |
| [Power](matrix_power.md) | Raise a square matrix to an integer power | [Products](matrix_products.md) |
| [Prod](matrix_prod.md) | Return the product of matrix/vector elements, which can also be executed for the given axis | [Statistics](matrix_statistics.md) |
| [Ptp](matrix_ptp.md) | Return the range of values of a matrix/vector or of the given matrix axis | [Statistics](matrix_statistics.md) |
| [QR](matrix_qr.md) | Compute the qr factorization of a matrix | [Transformations](matrix_decompositions.md) |
| [Quantile](matrix_quantile.md) | Return the specified quantile of values of matrix/vector elements or elements along the specified axis | [Statistics](matrix_statistics.md) |
| [Random](matrix_random.md) | Static function. Create and return a new matrix or vector filled with random values. Random values are generated uniformly within the specified range | [Initialization](matrix_initialization.md) |
| [Rank](matrix_rank.md) | Return matrix rank using the Gaussian method | [Features](matrix_characteristics.md) |
| [RegressionMetric](matrix_regressionmetrics.md) | Compute the regression metric as the deviation error from the regression line constructed on the specified data array | [Statistics](matrix_statistics.md) |
| [Reshape](matrix_reshape.md) | Change the shape of a matrix without changing its data | [Manipulations](matrix_manipulations.md) |
| [Resize](matrix_resize.md) | Return a new matrix with a changed shape and size | [Manipulations](matrix_manipulations.md) |
| [Row](matrix_row.md) | Return a row vector. Write the vector to the specified row | [Manipulations](matrix_manipulations.md) |
| [Rows](matrix_rows.md) | Return the number of rows in a matrix | [Features](matrix_characteristics.md) |
| [Set](matrix_set.md) | Sets the value for a vector element by the specified index | [Manipulations](matrix_manipulations.md) |
| [Size](matrix_size.md) | Return the size of vector | [Features](matrix_characteristics.md) |
| [SLogDet](matrix_slogdet.md) | Compute the sign and logarithm of the determinant of an matrix | [Features](matrix_characteristics.md) |
| [Solve](matrix_solve.md) | Solve a linear matrix equation or a system of linear algebraic equations | [Solutions](matrix_solves.md) |
| [Sort](matrix_sort.md) | Sort by place | [Manipulations](matrix_manipulations.md) |
| [Spectrum](matrix_spectrum.md) | Compute spectrum of a matrix as the set of its eigenvalues from the product AT*A | [Features](matrix_characteristics.md) |
| [Split](matrix_split.md) | Split a matrix into multiple submatrices | [Manipulations](matrix_manipulations.md) |
| [Std](matrix_std.md) | Return the standard deviation of values of matrix/vector elements or elements along the specified axis | [Statistics](matrix_statistics.md) |
| [Sum](matrix_sum.md) | Return the sum of matrix/vector elements, which can also be executed for the given axis (axes) | [Statistics](matrix_statistics.md) |
| [SVD](matrix_svd.md) | Singular value decomposition | [Transformations](matrix_decompositions.md) |
| [SwapCols](matrix_swapcols.md) | Swap columns in a matrix | [Manipulations](matrix_manipulations.md) |
| [SwapRows](matrix_swaprows.md) | Swap rows in a matrix | [Manipulations](matrix_manipulations.md) |
| [Trace](matrix_trace.md) | Return the sum along diagonals of the matrix | [Features](matrix_characteristics.md) |
| [Transpose](matrix_transpose.md) | Transpose (swap the axes) and return the modified matrix | [Manipulations](matrix_manipulations.md) |
| [Tri](matrix_tri.md) | Construct a matrix with ones on a specified diagonal and below, and zeros elsewhere | [Initialization](matrix_initialization.md) |
| [TriL](matrix_tril.md) | Return a copy of a matrix with elements above the k-th diagonal zeroed. Lower triangular matrix | [Manipulations](matrix_manipulations.md) |
| [TriU](matrix_triu.md) | Return a copy of a matrix with the elements below the k-th diagonal zeroed. Upper triangular matrix | [Manipulations](matrix_manipulations.md) |
| [Var](matrix_var.md) | Compute the variance of values of matrix/vector elements | [Statistics](matrix_statistics.md) |
| [Vsplit](matrix_vsplit.md) | Split a matrix vertically into multiple submatrices. Same as Split with axis=1 | [Manipulations](matrix_manipulations.md) |
| [Zeros](matrix_zeros.md) | Create and return a new matrix filled with zeros | [Initialization](matrix_initialization.md) |