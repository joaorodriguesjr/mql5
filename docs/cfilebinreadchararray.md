ReadCharArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / ReadCharArray

[![Previous](previous.png)](cfilebinreadstring.md) 
[![Next](next.png)](cfilebinreadshortarray.md)

ReadCharArray

Reads an array of char or uchar type variables from file.

```
bool  ReadCharArray(
   char&  array[],            // array
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