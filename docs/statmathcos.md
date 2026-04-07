MathCos



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathCos

[![Previous](previous.png)](statmathsin.md) 
[![Next](next.png)](statmathtan.md)

MathCos

Calculates the values of the cos(x) function for array elements.

Version with output of the results to a new array:

```
bool  MathCos(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathCos(
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