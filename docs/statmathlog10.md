MathLog10



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathLog10

[![Previous](previous.png)](statmathlog2.md) 
[![Next](next.png)](statmathlog1p.md)

MathLog10

Calculates the logarithm to the base 10 for the array elements. 

Version with output of the results to a new array:

```
bool  MathLog10(
   const double&   array[],   // array of values
   double&         result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathLog10(
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