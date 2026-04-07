MathCumulativeDistributionEmpirical



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathCumulativeDistributionEmpirical

[![Previous](previous.png)](statmathprobabilitydensityempirical.md) 
[![Next](next.png)](fuzzy_logic.md)

MathCumulativeDistributionEmpirical

The function calculates the empirical cumulative distribution function (cdf) for random values from an array.

```
bool  MathCumulativeDistributionEmpirical(
   const double&  array[],   // array of random values
   const int      count,     // the number of pairs
   double&        x[],       // array of x values
   double&        cdf[]      // array of cdf values
   )
```

Parameters

array[]

[in] Array of random values. 

count

[in] The number of (x, cdf(x)) pairs.

x[]

[out] Array to output the x values. 

cdf[]

[out] Array to output the cdf(x) values. 

Return Value

Returns true if successful, otherwise false.