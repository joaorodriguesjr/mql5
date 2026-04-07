Checking Object Pointer



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Named Constants](namedconstants.md) / Checking Object Pointer

[![Previous](previous.png)](uninit.md) 
[![Next](next.png)](otherconstants.md)

Checking Object Pointer

The [CheckPointer()](checkpointer.md) function is used for checking the type of the [object pointer](object_pointers.md). The function returns a value of the ENUM\_POINTER\_TYPE enumeration. If an incorrect pointer is used, the program execution will be immediately terminated.

Objects created by the [new()](newoperator.md) operator are of POINTER\_DYNAMIC type. The [delete() operator](deleteoperator.md) can and should be used only for such pointers.

All other pointers are of POINTER\_AUTOMATIC type, which means that this object has been created automatically by the mql5 program environment. Such objects are deleted automatically after being used.

ENUM\_POINTER\_TYPE

| Constant | Description |
| --- | --- |
| POINTER\_INVALID | Incorrect pointer |
| POINTER\_DYNAMIC | Pointer of the object created by the [new()](newoperator.md) operator |
| POINTER\_AUTOMATIC | Pointer of any objects created automatically (not using new()) |

See also

[Runtime errors](errors.md), [Object Delete Operator delete](deleteoperator.md), [CheckPointer](checkpointer.md)