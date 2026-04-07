MathMomentsT



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [T-distribution](student.md) / MathMomentsT

[![Previous](previous.png)](mathrandomt.md) 
[![Next](next.png)](noncentralstudent.md)

MathMomentsT

Calculates the theoretical numerical values of the first 4 moments of the Student's t-distribution with the nu parameter.

```
double  MathMomentsT(
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

[in]  Parameter of distribution (number of degrees of freedom).

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