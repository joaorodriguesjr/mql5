TryGetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [IList<T](ilist.md)/

[![Previous](previous.png)](ilist.md) 
[![Next](next.png)](ilisttrysetvalue.md)

TryGetValue

Gets a list element at the specified index.

```
bool TryGetValue(
   const int  index,     // element index
   T&         value      // a variable for writing
   );
```

Parameters

index

[in]  The index of the element from the list.

&value

[out]  The variable to which the specified value of the element from the list will be written.

Return Value

Returns true on successful, or false otherwise.