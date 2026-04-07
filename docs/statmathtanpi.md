MathTanPi



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathTanPi

[![Previous](previous.png)](statmathcospi.md) 
[![Next](next.png)](statmathabs.md)

MathTanPi

Calculates the values of the tan(pi*x) function for array elements.

Version with output of the result to a new array:

```
bool  MathTanPi(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the result to the original array:

```
bool  MathTanPi(
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