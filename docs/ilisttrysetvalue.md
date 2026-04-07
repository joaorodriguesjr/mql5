TrySetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [IList<T](ilist.md)/

[![Previous](previous.png)](ilisttrygetvalue.md) 
[![Next](next.png)](ilistinsert.md)

TrySetValue

Changes a value from the list at the specified index.

```
bool TrySetValue(
   const int  index,     // element index
   T          value      // new value
   );
```

Parameters

index

[in]  The index of the element from the list.

value

[in] The new value to assign to the specified list element.

Return Value

Returns true on successful, or false otherwise.