MathRandomUniform



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Uniform distribution](unifrom.md) / MathRandomUniform

[![Previous](previous.png)](mathquantileuniform.md) 
[![Next](next.png)](mathmomentsuniform.md)

MathRandomUniform

Generates a pseudorandom variable distributed according to the law of uniform distribution with the a and b parameters. In case of error it returns [NaN](double.md).

```
double  MathRandomUniform(
   const double  a,              // distribution parameter a (lower bound)
   const double  b,              // distribution parameter b (upper bound)
   int&          error_code      // variable to store the error code
   );
```

Generates pseudorandom variables distributed according to the law of uniform distribution with the a and b parameters. In case of error it returns false. Analog of the [runif()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Uniform.md) in R.

```
bool  MathRandomUniform(
   const double  a,              // distribution parameter a (lower bound)
   const double  b,              // distribution parameter b (upper bound)
   const int     data_count,     // amount of required data
   double&       result[]        // array with values of pseudorandom variables
   );
```

Parameters

a

[in]  Distribution parameter a (lower bound).

b

[in]  Distribution parameter b (upper bound).

error\_code

[out]  Variable to store the error code.

data\_count

[out]  Amount of required data.

result[]

[out]  Array to obtain the values of pseudorandom variables.