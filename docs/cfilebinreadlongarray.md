ReadLongArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / ReadLongArray

[![Previous](previous.png)](cfilebinreadintegerarray.md) 
[![Next](next.png)](cfilebinreadfloatarray.md)

ReadLongArray

Reads an array of long or ulong type variables from file.

```
bool  ReadLongArray(
   long&  array[],            // array
   int    start_item=0,       // start element
   int    items_count=-1      // number of elements
   )
```

Parameters

array[]

[in]  Reference to the variable for placing read data.

start\_item=0

[in]  Start element to read from.

items\_count=-1

[in]  Number of elements to read (-1 - read to the end of file).

Return Value

true - successful, false - cannot read the data.