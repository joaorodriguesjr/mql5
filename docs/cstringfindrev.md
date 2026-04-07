FindRev



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strings](stringoperations.md)  /  [CString](cstring.md) / FindRev

[![Previous](previous.png)](cstringfind.md) 
[![Next](next.png)](cstringremove.md)

FindRev

Searches for the last match of a substring.

```
int  FindRev(
   const string  substring      // substring
   ) const;
```

Parameters

substring

[in]  Sample substring to search for.

Return Value

The index of the last match of a substring (-1 - substring is not found).