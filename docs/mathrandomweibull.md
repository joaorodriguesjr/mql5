MathRandomWeibull



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Weibull distribution](weibull.md) / MathRandomWeibull

[![Previous](previous.png)](mathquantileweibull.md) 
[![Next](next.png)](mathmomentsweibull.md)

MathRandomWeibull

Generates a pseudorandom variable distributed according to the law of Weibull distribution with the a and b parameters. In case of error it returns [NaN](double.md).

```
double  MathRandomWeibull(
   const double  a,              // parameter of the distribution (shape)
   const double  b,              // parameter of the distribution (scale)
   int&          error_code      // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the law of Weibull distribution with the a and b parameters. In case of error it returns false. Analog of the [rweibull()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Weibull.md) in R.

```
bool  MathRandomWeibull(
   const double  a,              // parameter of the distribution (shape)
   const double  b,              // parameter of the distribution (scale)
   const int     data_count,     // amount of required data
   double&       result[]        // array with values of pseudorandom variables
   );
```

Parameters

a

[in]  Parameter of the distribution (scale).

b

[in]  Parameter of the distribution (shape).  

error\_code

[out]  Variable to store the error code.

data\_count

[out]  Amount of required data.

result[]

[out]  Array to obtain the values of pseudorandom variables.