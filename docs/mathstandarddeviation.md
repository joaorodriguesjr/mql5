MathStandardDeviation



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Statistical Characteristics](array_stat.md) / MathStandardDeviation

[![Previous](previous.png)](mathmedian.md) 
[![Next](next.png)](mathaveragedeviation.md)

MathStandardDeviation

Calculates the standard deviation of array elements. Analog of the [sd()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/sd.md) in R.

```
double  MathStandardDeviation(
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

The standard deviation of array elements. In case of error it returns [NaN](double.md) (not a number).