MathMean



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Statistical Characteristics](array_stat.md) / MathMean

[![Previous](previous.png)](array_stat.md) 
[![Next](next.png)](mathvariance.md)

MathMean

Calculates the mean (first moment) of array elements. Analog of the [mean()](https://stat.ethz.ch/R-manual/R-devel/library/base/html/mean.md) in R.

```
double  MathMean(
   const double&  array[]                // array with data
   );
```

Parameters

array

[in]  Array with data for calculation of the mean.

start=0

[in]  Initial index for calculation.

count=WHOLE\_ARRAY

[in]  The number of elements for calculation.

Return Value

The mean of array elements. In case of error it returns [NaN](double.md) (not a number).