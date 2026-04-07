ReadInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / ReadInteger

[![Previous](previous.png)](cfilebinreadshort.md) 
[![Next](next.png)](cfilebinreadlong.md)

ReadInteger

Reads int or uint type variable from file.

```
bool  ReadInteger(
   int&  value      // variable
   )
```

Parameters

value

[in]  Reference to the variable for placing read data.

Return Value

true - successful, false - cannot read the data.