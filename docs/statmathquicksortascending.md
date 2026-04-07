MathQuickSortAscending



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Statistics](stat.md)  /  [Subfunctions](mathsubfunctions.md) / MathQuickSortAscending

[![Previous](previous.png)](statmathunique.md) 
[![Next](next.png)](statmathquicksortdescending.md)

MathQuickSortAscending

The function for the simultaneous ascending sorting of the array[] and indices[] arrays using the QuickSort algorithm. 

```
void  MathQuickSortAscending(
   double&  array[],     // array of values
   int&     indices[],   // array of indexes
   int      first,       // initial value
   int      last         // final value
   )
```

Parameters

array[]

[in][out] Array to be sorted. 

indices[]

[in][out] Array to store the indexes of the original array.

first

[in] Index of the element to start sorting from.

last

[in] Index of the element to stop sorting at.