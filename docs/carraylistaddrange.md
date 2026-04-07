AddRange



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CArrayList<T](carraylist.md)/

[![Previous](previous.png)](carraylistadd.md) 
[![Next](next.png)](carraylistinsert.md)

AddRange

Adds a collection or an array of elements to the list.

The version that adds an array.

```
bool AddRange(
   const T&  array[]               // an array to be added
   );
```

The version that adds a collection.

```
bool AddRange(
   ICollection<T>*  collection     // a collection to be added
   );
```

Parameters

&array[]

[in]  An array to be added.

*collection

[in]  A collection to be added.

Return Value

Returns true on successful, or false otherwise.