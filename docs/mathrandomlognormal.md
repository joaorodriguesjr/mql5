MathRandomLognormal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Log-normal distribution](lognormal.md) / MathRandomLognormal

[![Previous](previous.png)](mathquantilelognormal.md) 
[![Next](next.png)](mathmomentslognormal.md)

MathRandomLognormal

Generates a pseudorandom variable distributed according to the log-normal law with the mu sigma parameters. In case of error it returns [NaN](double.md).

```
double  MathRandomLognormal(
   const double  mu,             // logarithm of the expected value (log mean)
   const double  sigma,          // logarithm of the root-mean-square deviation (log standard deviation)
   int&          error_code      // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the log-normal law with the mu sigma parameters. In case of error it returns false. Analog of the [rlnorm()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Lognormal.md) in R.

```
double  MathRandomLognormal(
   const double  mu,             // logarithm of the expected value (log mean)
   const double  sigma,          // logarithm of the root-mean-square deviation (log standard deviation)
   const int     data_count,     // amount of required data
   double&       result[]        // array with values of pseudorandom variables
   );
```

Parameters

mu

[in]  Logarithm of the expected value (log\_mean).

sigma

[in]  Logarithm of the root-mean-square deviation (log standard deviation).

data\_count

[in]   Amount of required data.

error\_code

[out]  Variable to store the error code.

result[]

[out]  Array with values of pseudorandom variables.