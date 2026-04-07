StringBufferLen



[MQL5 Reference](index.md)  /  [String Functions](strings.md) / StringBufferLen

[![Previous](previous.png)](stringadd.md) 
[![Next](next.png)](stringcompare.md)

StringBufferLen

The function returns the size of buffer allocated for the string.

```
int  StringBufferLen(
   string  string_var      // string
   )
```

Parameters

string\_var

[in]  String.

Return Value

The value 0 means that the string is constant and buffer size can't be changed. -1 means that the string belongs to the client terminal, and modification of the buffer contents can have indeterminate results.

Example:

```
void OnStart()
  {
   long length=1000;
   string a="a",b="b";
//---
   long i;
   Print("before: StringBufferLen(a) = ",StringBufferLen(a),
         "  StringLen(a) = ",StringLen(a));
   for(i=0;i<length;i++)
     {
      StringAdd(a,b);
     }
   Print("after: StringBufferLen(a) = ",StringBufferLen(a),
         "  StringLen(a) = ",StringLen(a));
  }
```

See also

[StringAdd](stringadd.md), [StringInit](stringinit.md), [StringLen](stringlen.md), [StringFill](stringfill.md)