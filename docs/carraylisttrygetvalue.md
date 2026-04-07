TryGetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CArrayList<T](carraylist.md)/

[![Previous](previous.png)](carraylisttrimexcess.md) 
[![Next](next.png)](carraylisttrysetvalue.md)

TryGetValue

Gets an element of the list at the specified index.

```
bool TryGetValue(
   const int  index,     // index
   T&         value      // a variable to write
   );
```

Parameters

index

[in]  The index of the list element the value of which you want to get.

&value

[out]  The variable to write the element value to.

Return Value

Returns true on successful, or false otherwise.