MathLog



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathLog

[![Previous](previous.png)](statmathpow.md) 
[![Next](next.png)](statmathlog2.md)

MathLog

Calculates the values of the log(x) function for array elements. 

Version for calculating the natural logarithm with output of the results to a new array.

```
bool  MathLog(
   const double&  array[],      // array of values
   double&        result[]      // array of results
   )
```

Version for calculating the natural logarithm with output of the results to the original array.

```
bool  MathLog(
   double&        array[]       // array of values
   )
```

Version for calculating the logarithm to a specified base with output of the results to a new array. 

```
bool  MathLog(
   const double&   array[],     // array of values
   const double    base,        // base of the logarithm
   double&         result[]     // array of results
   )
```

Version for calculating the logarithm to a specified base with output of the results to the original array. 

```
bool  MathLog(
   double&         array[],     // array of values
   const double    base         // base of the logarithm
   )
```

Parameters

array[]

[in] Array of values. 

base

[in] The base of the logarithm.

array[]

[out] Array of output values.

result[]

[out] Array of output values. 

Return Value

Returns true if successful, otherwise false.