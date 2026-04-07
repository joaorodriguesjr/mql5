MathMedian



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Statistical Characteristics](array_stat.md) / MathMedian

[![Previous](previous.png)](mathmoments.md) 
[![Next](next.png)](mathstandarddeviation.md)

MathMedian

Calculates the median value of array elements. Analog of the [median()](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/median.md) in R.

```
double  MathMedian(
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

The median value of array elements. In case of error it returns [NaN](double.md) (not a number).