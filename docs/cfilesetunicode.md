SetUnicode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / SetUnicode

[![Previous](previous.png)](cfileflags.md) 
[![Next](next.png)](cfilesetcommon.md)

SetUnicode

Sets/clears the FILE\_UNICODE flag.

```
void  SetUnicode(
   bool  unicode      // flag value
   )
```

Parameters

unicode

[in]  New value for FILE\_UNICODE flag.

Note

The result of string operations is dependent on the FILE\_UNICODE flag. If it is false, the ANSI codes are used (one byte symbols). If it set, the UNICODE codes are used (two byte symbols). If the file is already opened, the flag cannot be changed.