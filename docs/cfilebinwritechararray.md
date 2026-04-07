WriteCharArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / WriteCharArray

[![Previous](previous.png)](cfilebinwritestring.md) 
[![Next](next.png)](cfilebinwriteshortarray.md)

WriteCharArray

Writes an array of char or uchar type variables to file.

```
uint  WriteCharArray(
   char&  array[],            // array
   int    start_item=0,       // start element
   int    items_count=-1      // number of elements
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