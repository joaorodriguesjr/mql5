WriteString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / WriteString

[![Previous](previous.png)](cfilebinwritedouble.md) 
[![Next](next.png)](cfilebinwritechararray.md)

WriteString

Writes string type variable to file.

```
uint  WriteString(
   const string  value      // value
   )
```

Parameters

value

[in]  String to write.

Return Value

Number of bytes written.

WriteString

Writes string type variable to file.

```
uint  WriteString(
   const string  value,     // value
   int           size       // size
   )
```

Parameters

value

[in]  String to write.

size

[in] Number of bytes to write.

Return Value

Number of bytes written.