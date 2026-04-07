SetCommon



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / SetCommon

[![Previous](previous.png)](cfilesetunicode.md) 
[![Next](next.png)](cfileopen.md)

SetCommon

Sets/clears the FILE\_COMMON flag.

```
void  SetCommon(
   bool  common      // flag value
   )
```

Parameters

common

[in]  New value for FILE\_COMMON flag.

Note

The FILE\_COMMON flag determines the current working folder. If it is false, the  local terminal folder is used as the current working folder. If it is true, the common data folder is used as the current working folder. If the file is already opened, the flag cannot be changed.