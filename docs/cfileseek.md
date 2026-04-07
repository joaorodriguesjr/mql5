Seek



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / Seek

[![Previous](previous.png)](cfiletell.md) 
[![Next](next.png)](cfileflush.md)

Seek

Sets file pointer's position.

```
void  Seek(
   long                offset,     // offset
   ENUM_FILE_POSITION  origin      // origin
   )
```

Parameters

offset

[in]  File offset in bytes (can be negative).

origin

[in]  Origin of the offset.

Return Value

true - successful, false - cannot change the file pointer.