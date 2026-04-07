TrySetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CArrayList<T](carraylist.md)/

[![Previous](previous.png)](carraylisttrygetvalue.md) 
[![Next](next.png)](carraylistadd.md)

TrySetValue

Sets the value of the list element at the specified index.

```
bool TrySetValue(
   const int  index,     // index
   T          value      // element value
   );
```

Parameters

index

[in]  The index of the list element the value of which you want to set.

value

[in]  Sets the value of the list element.

Return Value

Returns true on successful, or false otherwise.