Integer Types



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Data Types](types.md) / Integer Types

[![Previous](previous.png)](types.md) 
[![Next](next.png)](integertypes.md)

Integer Types

In MQL5 integers are represented by eleven types. Some types can be used together with other ones, if required by the program logic, but in this case it's necessary to remember the rules of [typecasting](casting.md).

The table below lists the characteristics of each type. Besides, the last column features a type in C++ corresponding to each type.

| Type | Size in Bytes | Minimum Value | Maximum Value | C++ Analog |
| --- | --- | --- | --- | --- |
| [char](integertypes.md#char) | 1 | -128 | 127 | char |
| [uchar](integertypes.md#uchar) | 1 | 0 | 255 | unsigned char, BYTE |
| [bool](boolconst.md) | 1 | 0(false) | 1(true) | bool |
| [short](integertypes.md#short) | 2 | -32 768 | 32 767 | short, wchar\_t |
| [ushort](integertypes.md#ushort) | 2 | 0 | 65 535 | unsigned short, WORD |
| [int](integertypes.md#int) | 4 | - 2 147 483 648 | 2 147 483 647 | int |
| [uint](integertypes.md#uint) | 4 | 0 | 4 294 967 295 | unsigned int, DWORD |
| [color](color.md) | 4 | -1 | 16 777 215 | int, COLORREF |
| [long](integertypes.md#long) | 8 | -9 223 372 036 854 775 808 | 9 223 372 036 854 775 807 | \_\_int64 |
| [ulong](integertypes.md#ulong) | 8 | 0 | 18 446 744 073 709 551 615 | unsigned \_\_int64 |
| [datetime](datetime.md) | 8 | 0 (1970.01.01 0:00:00) | 32 535 244 799 (3000.12.31 23:59:59) | \_\_time64\_t |

Integer type values can also be presented as numeric constants, color literals, date-time literals, [character constants](symbolconstants.md) and [enumerations](enumeration.md).

 

Additional integer type aliases (for C/C++ compatibility)

To simplify the porting of code from other languages, such as C and C++, aliases for standard integer types were added to the MQL5 language. These aliases do not introduce new types, but are alternative names for existing types in MQL5. They can be used in all contexts where base types are applicable.

| Type | Corresponds to MQL5 type | Size in Bytes | Sign | Minimum Value | Maximum Value |
| --- | --- | --- | --- | --- | --- |
| int8\_t | [char](integertypes.md#char) | 8 | signed | -128 | 127 |
| uint8\_t | [uchar](integertypes.md#uchar) | 8 | unsigned | 0 | 255 |
| int16\_t | [short](integertypes.md#short) | 16 | signed | -32 768 | 32 767 |
| uint16\_t | [ushort](integertypes.md#ushort) | 16 | unsigned | 0 | 65 535 |
| int32\_t | [int](integertypes.md#int) | 32 | signed | - 2 147 483 648 | 2 147 483 647 |
| uint32\_t | [uint](integertypes.md#uint) | 32 | unsigned | 0 | 4 294 967 295 |
| int64\_t | [long](integertypes.md#long) | 64 | signed | -9 223 372 036 854 775 808 | 9 223 372 036 854 775 807 |
| uint64\_t | [ulong](integertypes.md#ulong) | 64 | unsigned | 0 | 18 446 744 073 709 551 615 |

These aliases are useful when porting existing libraries and algorithms from C/C++ to MQL5, especially in projects with a high level of platform compatibility. All new names are available in scripts, EAs and indicators.

 

See also

[Conversion Functions](convert.md), [Numerical Type Constants](typeconstants.md)