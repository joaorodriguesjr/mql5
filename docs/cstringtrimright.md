TrimRight



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strings](stringoperations.md)  /  [CString](cstring.md) / TrimRight

[![Previous](previous.png)](cstringtrimleft.md) 
[![Next](next.png)](cstringclear.md)

TrimRight

Removes all characters within a set (as well as ' ','\t','\r','\n') at the end of a string from this string.

```
int  TrimRight(
   const string  targets      // set
   )
```

Parameters

targets

[in]  Set of characters to remove.

Return Value

Number of characters removed.