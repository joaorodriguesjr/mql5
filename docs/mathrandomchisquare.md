MathRandomChiSquare



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Chi-squared distribution](chisquare.md) / MathRandomChiSquare

[![Previous](previous.png)](mathquantilechisquare.md) 
[![Next](next.png)](mathmomentschisquare.md)

MathRandomChiSquare

Generates a pseudorandom variable distributed according to the law of chi-squared distribution with the nu parameter. In case of error it returns [NaN](double.md).

```
double  MathRandomChiSquare(
   const double  nu,            // parameter of distribution (number of degrees of freedom)
   int&          error_code     // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the law of chi-squared distribution with the nu parameter. In case of error it returns false. Analog of the [rchisq()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Chisquare.md) in R.

```
bool  MathRandomChiSquare(
   const double  nu,             // parameter of distribution (number of degrees of freedom)
   const int     data_count,     // amount of required data
   double&       result[]        // array with values of pseudorandom variables
   );
```

Parameters

nu

[in]  Parameter of distribution (number of degrees of freedom).

error\_code

[out]  Variable to store the error code.

data\_count

[out]  Amount of required data.

result[]

[out]  Array to obtain the values of pseudorandom variables.