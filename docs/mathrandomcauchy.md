MathRandomCauchy



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Cauchy distribution](cauchy.md) / MathRandomCauchy

[![Previous](previous.png)](mathquantilecauchy.md) 
[![Next](next.png)](mathmomentscauchy.md)

MathRandomCauchy

Generates a pseudorandom variable distributed according to the law of Cauchy distribution with the a and b parameters. In case of error it returns [NaN](double.md).

```
double  MathRandomCauchy(
   const double  a,              // mean parameter of the distribution
   const double  b,              // scale parameter of the distribution
   int&          error_code      // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the law of Cauchy distribution with the a and b parameters. In case of error it returns false. Analog of the [rcauchy()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Cauchy.md) in R.

```
bool  MathRandomCauchy(
   const double  a,              // mean parameter of the distribution
   const double  b,              // scale parameter of the distribution
   const int     data_count,     // amount of required data
   double&       result[]        // array with values of pseudorandom variables
   );
```

Parameters

a

[in]  mean parameter of the distribution.

b

[in]  scale parameter of the distribution.

error\_code

[out]  Variable to store the error code.

data\_count

[out]  Amount of required data.

result[]

[out]  Array to obtain the values of pseudorandom variables.