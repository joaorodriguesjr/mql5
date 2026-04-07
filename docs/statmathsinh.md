MathSinh



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathSinh

[![Previous](previous.png)](statmathexpm1.md) 
[![Next](next.png)](statmathcosh.md)

MathSinh

Calculates the values of the sinh(x) function for array elements.

Version with output of the results to a new array:

```
bool  MathSinh(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathSinh(
   double&       array[]    // array of values
   )
```

Parameters

array[]

[in] Array of values.   

result[]

[out] Array of output values.   

array[]

[out] Array of output values. 

Return Value

Returns true if successful, otherwise false.