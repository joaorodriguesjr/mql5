MathRandomNormal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Normal Distribution](normal.md) / MathRandomNormal

[![Previous](previous.png)](mathquantilenormal.md) 
[![Next](next.png)](mathmomentsnormal.md)

MathRandomNormal

Generates a pseudorandom variable distributed according to the normal law with the mu and sigma parameters. In case of error it returns [NaN](double.md).

```
double  MathRandomNormal(
   const double  mu,             // expected value
   const double  sigma,          // root-mean-square deviation
   int&          error_code      // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the normal law with the mu and sigma parameters. In case of error it returns false. Analog of the [rnorm()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Normal.md) in R.

```
bool  MathRandomNormal(
   const double  mu,             // expected value
   const double  sigma,          // root-mean-square deviation
   const int     data_count,     // amount of required data
   double&       result[]        // array to obtain the pseudorandom variables
   );
```

Parameters

mu

[in]  mean parameter of the distribution (expected value).

sigma

[in]  sigma parameter of the distribution (root-mean-square deviation).

data\_count

[in]  The number of pseudorandom variables to be obtained.

error\_code

[out]  Variable to get the error code.

result[]

[out]  Array to obtain the values of pseudorandom variables.