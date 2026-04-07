MathBitwiseNot



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathBitwiseNot

[![Previous](previous.png)](statmathorder.md) 
[![Next](next.png)](statmathbitwiseand.md)

MathBitwiseNot

Calculates the result of bitwise NOT operation for array elements.

Version with output of the results to a new array:

```
bool  MathBitwiseNot(
   const int&  array[],   // array of values
   int&        result[]   // array of results
   )
```

Version with output of the results to the original array:

```
bool  MathBitwiseNot(
   int&        array[]    // array of values
   )
```

Parameters

array[]

[in] Array of values. 

array[]

[out] Array of output values. 

result[]

[out] Array of output values.

Return Value

Returns true if successful, otherwise false.