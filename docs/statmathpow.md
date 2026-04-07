MathPow



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathPow

[![Previous](previous.png)](statmathexp.md) 
[![Next](next.png)](statmathlog.md)

MathPow

Calculates the values of the pow(x, power) function for array elements. 

Version with output of the results to a new array:

```
bool  MathPow(
   const double&  array[],    // array of values
   const double   power,      // power
   double&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathPow(
   double&        array[],    // array of values
   const double   power       // power
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