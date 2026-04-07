Void Type and NULL Constant



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Data Types](types.md) / Void Type and NULL Constant

[![Previous](previous.png)](casting.md) 
[![Next](next.png)](typedef.md)

Void Type and NULL Constant

Syntactically the void type is a fundamental type along with types of char, uchar, bool, short, ushort, int, uint, color, long, ulong, datetime, float, double and string. This type is used either to indicate that the function does not return any value, or as a function parameter it denotes the absence of parameters.

The predefined constant variable NULL is of the void type. It can be assigned to variables of any other fundamental types without conversion. The comparison of fundamental type variables with the NULL value is allowed.

Example:

```
//--- If the string is not initialized, then assign our predefined value to it
if(some_string==NULL) some_string="empty";
```

Also NULL can be compared to pointers to objects created with the [new operator](newoperator.md).

See also

[Variables](variables.md), [Functions](function.md)