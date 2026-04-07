RemoveRange



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CArrayList<T](carraylist.md)/

[![Previous](previous.png)](carraylistremoveat.md) 
[![Next](next.png)](carraylistreverse.md)

RemoveRange

Removes a range of elements from the list.

```
bool RemoveRange(
   const int  start_index,     // the starting index
   const int  count            // the number of elements
   );
```

Parameters

start\_index

[in] The starting index from which the deletion begins.

count

[in]  The number of elements to be deleted.

Return Value

Returns true on successful, or false otherwise.