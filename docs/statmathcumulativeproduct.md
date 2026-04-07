MathCumulativeProduct



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathCumulativeProduct

[![Previous](previous.png)](statmathcumulativesum.md) 
[![Next](next.png)](statmathcumulativemin.md)

MathCumulativeProduct

Generates an array with the cumulative products.

Version with output of the results to a new array:

```
bool  MathCumulativeProduct(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathCumulativeProduct(
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