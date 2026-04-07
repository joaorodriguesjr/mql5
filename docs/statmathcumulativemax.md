MathCumulativeMax



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathCumulativeMax

[![Previous](previous.png)](statmathcumulativemin.md) 
[![Next](next.png)](statmathsin.md)

MathCumulativeMax

Generates an array with the cumulative maxima.

Version with output of the results to a new array:

```
bool  MathCumulativeMax(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathCumulativeMax(
   double&        array[]    // array of values
   )
```

Parameters

array[]

[in] Array of values. 

result[]

[out] Array of output values. 

array[]

[out] Array of output values.   

Return Value

Returns true if successful, otherwise false.