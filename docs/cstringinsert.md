Insert



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strings](stringoperations.md)  /  [CString](cstring.md) / Insert

[![Previous](previous.png)](cstringappend.md) 
[![Next](next.png)](cstringcompare.md)

Insert

Inserts a string to the specified position.

```
uint  Insert(
   uint          pos,     // position
   const string  str      // string
   )
```

Parameters

pos

[in]  Insert position.

str

[in]  String to insert.

Return Value

Resulted string length.

Insert

Inserts a string to the specified position from the CString class instance.

```
uint  Insert(
   uint      pos,     // position
   CString*  str      // pointer
   )
```

Parameters

pos

[in]  Position to insert into.

str

[in]  Pointer to the CString class instance to insert.

Return Value

Resulted string length.