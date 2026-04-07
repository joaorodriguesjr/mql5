Matrix and Vector Types



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md) / Matrix and Vector Types

[![Previous](previous.png)](matrix.md) 
[![Next](next.png)](matrix_enumerations.md)

Matrix and Vector Types

Matrix and vector are special data types in MQL5 which enable linear algebra operations. The following data types exist:

* matrix a matrix containing double elements.
* matrixf a matrix containing float elements.
* matrixc a matrix containing complex elements.
* vector a vector containing double elements.
* vectorf a vector containing float elements.
* vectorc a vector containing complex elements.

Template functions support notations like matrix<double>, matrix<float>, vector<double>, vector<float> instead of the corresponding types.

Matrix and vector initialization methods

| Function | Action |
| --- | --- |
| [Eye](matrix_eye.md) | Return a matrix with ones on the diagonal and zeros elsewhere |
| [Identity](matrix_identity.md) | Create an identity matrix of the specified size |
| [Ones](matrix_ones.md) | Create and return a new matrix filled with ones |
| [Zeros](matrix_zeros.md) | Create and return a new matrix filled with zeros |
| [Full](matrix_full.md) | Create and return a new matrix filled with given value |
| [Tri](matrix_tri.md) | Construct a matrix with ones at and below the given diagonal and zeros elsewhere |
| [Init](matrix_init.md) | Initialize a matrix or a vector |
| [Fill](matrix_fill.md) | Fill an existing matrix or vector with the specified value |