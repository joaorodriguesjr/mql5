WriteFloatArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / WriteFloatArray

[![Previous](previous.png)](cfilebinwritelongarray.md) 
[![Next](next.png)](cfilebinwritedoublearray.md)

WriteFloatArray

Writes an array of float type variables to file.

```
uint  WriteFloatArray(
   float&  array[],            // array
   int     start_item=0,       // start element
   int     items_count=-1      // number of elements
   )
```

Parameters

array[]

[in]  Array to write.

start\_item=0

[in]  Start element to write from.

items\_count=-1

[in]  Number of elements to write (-1 - whole array).

Return Value

Number of bytes written.