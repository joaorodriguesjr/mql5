SingularSpectrumAnalysisReconstructComponents



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [OpenBLAS](openblas.md)  /  [Singular Spectrum Analysis](ssa.md) / SingularSpectrumAnalysisReconstructComponents

[![Previous](previous.png)](ssa_for.md) 
[![Next](next.png)](ssa_rec.md)

SingularSpectrumAnalysisReconstructComponents

A method function for calculating reconstructed components of the input time series and their contributions.

Calculations for vector<double> and matrix<double> types

```
bool  vector::SingularSpectrumAnalysisReconstructComponents(
   ulong    window_length,      // window size for constructing the trajectory matrix
   matrix&  components,         // matrix of reconstructed components
   vector&  contributions       // vector of component contributions to the input series
   );
```

Calculations for vector<complex> and matrix<complex> types

```
bool  vector::SingularSpectrumAnalysisReconstructComponents(
   ulong    window_length,      // window size for constructing the trajectory matrix
   matrixc& components,         // matrix of reconstructed components
   vectorc& contributions       // vector of component contributions to the input series
   );
```

Parameters

window\_length

[in]  Window size for constructing the trajectory matrix, the number of components the input time series should be decomposed into.

components

[out]  A matrix of reconstructed components, where each column describes a separate component.

contributions

[out]  Vector of component contributions to the input series (eigenvalues of the covariance matrix of the input time series).

Return Value

The function returns 'true' on success or 'false' if an [error](errorcodes.md) occurs.

Note

The window\_length parameter value should be less than the size of the input time series. To construct a full-fledged trajectory matrix, the optimal size is considered to be approximately equal to half the size of the input time series.