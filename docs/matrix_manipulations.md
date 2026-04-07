Manipulations



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md) / Manipulations

[![Previous](previous.png)](matrix_random.md) 
[![Next](next.png)](matrix_hasnan.md)

Matrix and vector manipulations

These are methods for basic matrix operations: filling, copying, getting a part of a matrix, transposing, splitting and sorting.

There are also several methods for operations with matrix rows and columns.

| Function | Action |
| --- | --- |
| [HasNan](matrix_hasnan.md) | Return the number of [NaN](double.md) values in a matrix/vector |
| [ReplaceNan](matrix_replacenan.md) | Replace [NaN](double.md) values in a matrix/vector with the specified value and return the number of elements replaced |
| [ReplaceToZero](matrix_replacetozero.md) | Replace small values in a matrix/vector with the zero value and return the number of elements replaced |
| [Transpose](matrix_transpose.md) | Reverse or permute the axes of a matrix; returns the modified matrix |
| [TransposeConjugate](matrix_transposeconjugate.md) | Transposing a complex matrix with conjugation. Reverse or permute the axes of a matrix by changing a sign of an imaginary part of a complex number, return the modified matrix |
| [TriL](matrix_tril.md) | Return a copy of a matrix with elements above the k-th diagonal zeroed. Lower triangular matrix |
| [TriU](matrix_triu.md) | Return a copy of a matrix with elements below the k-th diagonal zeroed. Upper triangular matrix |
| [Diag](matrix_diag.md) | Extract a diagonal or construct a diagonal matrix |
| [Row](matrix_row.md) | Return a row vector. Write a vector to the specified row |
| [Col](matrix_col.md) | Return a column vector. Write a vector to the specified column |
| [Copy](matrix_copy.md) | Return a copy of the given matrix/vector |
| [Conjugate](matrix_conjugate.md) | Changing the sign of the imaginary part of a complex number, return the modified matrix or vector |
| [Concat](matrix_concat.md) | Concatenate 2 submatrices to one matrix. Concatenate 2 vectors to one vector |
| [Compare](matrix_compare.md) | Compare the elements of two matrices/vectors with the specified precision |
| [CompareByDigits](matrix_comparebydigits.md) | Compare the elements of two matrices/vectors up to significant digits |
| [CompareEqual](compareequal.md) | Perform an absolute comparison of two matrices by unfolding successive rows into one-dimensional vectors |
| [Flat](matrix_flat.md) | Allow addressing a matrix element through one index instead of two |
| [Clip](matrix_clip.md) | Limit the elements of a matrix/vector to a specified range of valid values |
| [Reshape](matrix_reshape.md) | Change the shape of a matrix without changing its data |
| [Resize](matrix_resize.md) | Return a new matrix with a changed shape and size |
| [Set](matrix_set.md) | Set the value for a vector element by the specified index |
| [SwapRows](matrix_swaprows.md) | Swap rows in a matrix |
| [SwapCols](matrix_swapcols.md) | Swap columns in a matrix |
| [Split](matrix_split.md) | Split a matrix into multiple submatrices |
| [Hsplit](matrix_hsplit.md) | Split a matrix horizontally into multiple submatrices. Same as [Split](matrix_split.md) with axis=0 |
| [Vsplit](matrix_vsplit.md) | Split a matrix vertically into multiple submatrices. Same as [Split](matrix_split.md) with axis=1 |
| [ArgSort](matrix_argsort.md) | Indirectly sort a matrix or vector. |
| [Sort](matrix_sort.md) | Sort a matrix or vector in place. |