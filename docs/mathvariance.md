MathVariance



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Statistical Characteristics](array_stat.md) / MathVariance

[![Previous](previous.png)](mathmean.md) 
[![Next](next.png)](mathskewness.md)

MathVariance

Calculates the variance (second moment) of array elements. Analog of the [var()](http://www.r-tutor.com/elementary-statistics/numerical-measures/variance) in R.

```
double  MathVariance(
   const double&  array[]                // array with data
   );
```

Parameters

array

[in]  Array with data for calculation.

start=0

[in]  Initial index for calculation.

count=WHOLE\_ARRAY

[in]  The number of elements for calculation.

Return Value

Variance of array elements. In case of error it returns [NaN](double.md) (not a number).