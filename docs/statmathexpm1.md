MathExpm1



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathExpm1

[![Previous](previous.png)](statmathkurtosis.md) 
[![Next](next.png)](statmathsinh.md)

MathExpm1

Calculates the values of the exp(x)-1 function for array elements.

Version with output of the results to a new array:

```
bool  MathExpm1(
   const double&   array[],   // array of values
   double&         result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathExpm1(
   double&         array[]    // array of values
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