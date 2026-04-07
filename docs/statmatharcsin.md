MathArcsin



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathArcsin

[![Previous](previous.png)](statmathtan.md) 
[![Next](next.png)](statmatharccos.md)

MathArcsin

Calculates the values of the arcsin(x) function for array elements.

Version with output of the results to a new array:

```
bool  MathArcsin(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathArcsin(
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