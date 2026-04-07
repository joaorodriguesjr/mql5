Data Type Identifiers



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Indicator Constants](indicatorconstants.md) / Data Type Identifiers

[![Previous](previous.png)](enum_indicator.md) 
[![Next](next.png)](environment_state.md)

Data Type Identifiers

When creating an indicator handle using the [IndicatorCreate()](indicatorcreate.md) function, an array of [MqlParam](mqlparam.md) type must be specified as the last parameter. Accordingly, the MqlParam structure, describing indicator, contains a special field type. This field contains information about the data type ([real](double.md), [integer](integer.md) or [string](stringconst.md) type) that are passed by a particular element of the array. The value of this field of the MqlParam structure may be one of ENUM\_DATATYPE values.

ENUM\_DATATYPE

| Identifier | Data type |
| --- | --- |
| TYPE\_BOOL | bool |
| TYPE\_CHAR | char |
| TYPE\_UCHAR | uchar |
| TYPE\_SHORT | short |
| TYPE\_USHORT | ushort |
| TYPE\_COLOR | color |
| TYPE\_INT | int |
| TYPE\_UINT | uint |
| TYPE\_DATETIME | datetime |
| TYPE\_LONG | long |
| TYPE\_ULONG | ulong |
| TYPE\_FLOAT | float |
| TYPE\_DOUBLE | double |
| TYPE\_STRING | string |

Each element of the array describes the corresponding input parameter of a created [technical indicator](indicators.md), so the type and order of elements in the array must be strictly maintained in accordance with the description.