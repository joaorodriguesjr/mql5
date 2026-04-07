MathRank



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathRank

[![Previous](previous.png)](statmathsignif.md) 
[![Next](next.png)](statmathcorrelationpearson.md)

MathRank

Calculates the ranks of array elements.

Version for working with an array of real values:

```
bool  MathRank(
   const double&  array[],  // array of values
   double&        rank[]    // array of ranks
   )
```

Version for working with an array of integer values:

```
bool  MathRank(
   const int&     array[],  // array of values
   double&        rank[]    // array of ranks
   )
```

Parameters

array[]

[in] Array of values. 

rank[]

[out] Array to output the ranks. 

Return Value

Returns true if successful, otherwise false.