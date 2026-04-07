MathRandomNegativeBinomial



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Negative binomial distribution](negativebinomial.md) / MathRandomNegativeBinomial

[![Previous](previous.png)](mathquantilenegativebinomial.md) 
[![Next](next.png)](mathmomentsmegativebinomial.md)

MathRandomNegativeBinomial

Generates a pseudorandom variable distributed according to the law of negative binomial distribution with the r and p parameters. In case of error it returns [NaN](double.md).

```
double  MathRandomNegativeBinomial(
   const double  r,              // number of successful tests
   const double  p,              // probability of success
   int&          error_code      // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the law of negative binomial distribution with the r and p parameters. In case of error it returns false. Analog of the [rweibull()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Weibull.md) in R.

```
bool  MathRandomNegativeBinomial(
   const double  r,              // number of successful tests
   const double  p,              // probability of success
   const int     data_count,     // amount of required data
   double&       result[]        // array with values of pseudorandom variables
   );
```

Parameters

r

[in]  Number of successful tests.

p

[in]  Probability of success.  

error\_code

[out]  Variable to store the error code.

data\_count

[out]  Amount of required data.

result[]

[out]  Array to obtain the values of pseudorandom variables.