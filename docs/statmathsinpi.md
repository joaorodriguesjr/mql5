MathSinPi



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathSinPi

[![Previous](previous.png)](statmatharctan.md) 
[![Next](next.png)](statmathcospi.md)

MathSinPi

Calculates the values of the sin(pi*x) function for array elements.

Version with output of the results to a new array:

```
bool  MathSinPi(
   const double&  array[],   // array of values
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathSinPi(
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