Reverse



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CArrayList<T](carraylist.md)/

[![Previous](previous.png)](carraylistremoverange.md) 
[![Next](next.png)](carraylistsort.md)

Reverse

Reverses the order of elements in the list.

The version for working with the entire list.

```
bool Reverse();
```

The version for working with the specified range of list elements.

```
bool Reverse(
   const int  start_index,     // the starting index
   const int  count            // the number of elements
   );
```

Parameters

start\_index

[in]  The starting index.

count

[in]  The number of list elements participating in the operation.

Return Value

Returns true on successful, or false otherwise.