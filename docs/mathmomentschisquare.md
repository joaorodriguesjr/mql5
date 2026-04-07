MathMomentsChiSquare



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Chi-squared distribution](chisquare.md) / MathMomentsChiSquare

[![Previous](previous.png)](mathrandomchisquare.md) 
[![Next](next.png)](noncentralchisquare.md)

MathMomentsChiSquare

Calculates the theoretical numerical values of the first 4 moments of the chi-squared distribution with the nu parameter.

```
double  MathMomentsChiSquare(
   const double  nu,             // parameter of distribution (number of degrees of freedom)
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