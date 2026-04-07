WriteIntegerArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / WriteIntegerArray

[![Previous](previous.png)](cfilebinwriteshortarray.md) 
[![Next](next.png)](cfilebinwritelongarray.md)

WriteIntegerArray

Writes an array of int or uint type variables to file.

```
uint  WriteIntegerArray(
   int&  array[],            // array
   int   start_item=0,       // start element
   int   items_count=-1      // number of elements
   )
```

Parameters

array[]

[in]  Array to write.

start\_item=0

[in]  Start element to write from.

items\_count=-1

[in]  Number of elements to  write (-1 - whole array).

Return Value

Number of bytes written.