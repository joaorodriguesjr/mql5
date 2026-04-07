Insert



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CArrayList<T](carraylist.md)/

[![Previous](previous.png)](carraylistaddrange.md) 
[![Next](next.png)](carraylistinsertrange.md)

Insert

Inserts an element into the list at the specified index.

```
bool Insert(
   const int  index,     // index to insert at
   T          item       // the value to be inserted
   );
```

Parameters

index

[in]  The index to insert at.

item

[in] The value to be inserted at the specified index.

Return Value

Returns true on successful, or false otherwise.