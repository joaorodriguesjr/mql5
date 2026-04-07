MathBinomialCoefficient



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathBinomialCoefficient

[![Previous](previous.png)](statmathgammaincomplete.md) 
[![Next](next.png)](statmathbinomialcoefficientlog.md)

MathBinomialCoefficient

Calculates the binomial coefficient: C(n,k)=n!/(k!*(n-k)!).

```
long  MathBinomialCoefficient(
   const int  n,      // the total number of elements
   const int  k       // the number of elements in combination
   )
```

Parameters

n

[in] The number of elements. 

k

[in] The number of elements for each combination. 

Return Value

The number of combinations of N choose K.