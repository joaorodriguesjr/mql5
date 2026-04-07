MathFloor



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathFloor

[![Previous](previous.png)](statmathceil.md) 
[![Next](next.png)](statmathsqrt.md)

MathFloor

Returns the nearest smaller integers for array elements.

Version with output of the results to a new array:

```
bool  MathFloor(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathFloor(
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