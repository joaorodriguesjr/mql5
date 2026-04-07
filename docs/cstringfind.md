Find



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strings](stringoperations.md)  /  [CString](cstring.md) / Find

[![Previous](previous.png)](cstringreverse.md) 
[![Next](next.png)](cstringfindrev.md)

Find

Searches for the first match of a substring from a specified position.

```
int  Find(
   uint          start,         // position
   const string  substring      // substring
   ) const;
```

Parameters

start

[in]  Initial position for substring search.

substring

[in]  Sample substring to search for.

Return Value

The index of the first match of a substring (-1 - substring is not found).