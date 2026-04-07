MathAverageDeviation



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Statistical Characteristics](array_stat.md) / MathAverageDeviation

[![Previous](previous.png)](mathstandarddeviation.md) 
[![Next](next.png)](normal.md)

MathAverageDeviation

Calculates the average absolute deviation of array elements. Analog of the [aad()](http://artax.karlin.mff.cuni.cz/r-help/library/lsr/html/aad.md) in R.

```
double  MathAverageDeviation(
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

The average absolute deviation of array elements. In case of error it returns [NaN](double.md) (not a number).