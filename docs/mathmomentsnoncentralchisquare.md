MathMomentsNoncentralChiSquare



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Noncentral chi-squared distribution](noncentralchisquare.md) / MathMomentsNoncentralChiSquare

[![Previous](previous.png)](mathrandomnoncentralchisquare.md) 
[![Next](next.png)](exponential.md)

MathMomentsNoncentralChiSquare

Calculates the theoretical numerical values of the first 4 moments of the noncentral chi-squared distribution with the nu and sigma parameters.

```
double  MathMomentsNoncentralChiSquare(
   const double  nu,             // parameter of distribution (number of degrees of freedom)
   const double  sigma,          // noncentrality parameter
   double&       mean,           // variable for the mean
   double&       variance,       // variable for the variance  
   double&       skewness,       // variable for the skewness
   double&       kurtosis,       // variable for the kurtosis
   int&          error_code      // variable for the error code
   );
```

Parameters

nu

[in]   Parameter of distribution (number of degrees of freedom).

sigma

[in]  Noncentrality parameter.

mean

[out]  Variable to get the mean value.

variance

[out]  Variable to get the variance.

skewness

[out]  Variable to get the skewness.

kurtosis

[out]  Variable to get the kurtosis.

error\_code

[out]  Variable to get the error code.

Return Value

Returns true if calculation of the moments has been successful, otherwise false.