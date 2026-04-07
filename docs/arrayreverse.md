ArrayReverse<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / ArrayReverse<T

[![Previous](previous.png)](arraylastindexof.md) 
[![Next](next.png)](compare.md)

ArrayReverse

Changes the sequence of elements in a one-dimensional array.

```
template<typename T>
bool ArrayReverse(
   T&         array[],         // the source array
   const int  start_index,     // the starting index
   const int  count            // the number of elements
   );
```

Parameters

&array[]

[out]  The source array.

start\_index

[in]  The starting index.

count

[in]  The number of array elements participating in the operation.

Return Value

Returns true on successful, or false otherwise.