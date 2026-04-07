Conversion Functions



[MQL5 Reference](index.md) / Conversion Functions

[![Previous](previous.png)](blasl3her2k.md) 
[![Next](next.png)](chartostring.md)

Conversion Functions

This is a group of functions that provide conversion of data from one format into another.

The [NormalizeDouble()](normalizedouble.md) function must be specially noted as it provides the necessary accuracy of the price presentation. In trading operations, no unnormalized prices may be used if their accuracy even a digit exceeds that required by the trade server.

| Function | Action |
| --- | --- |
| [CharToString](chartostring.md) | Converting a symbol code into a one-character string |
| [DoubleToString](doubletostring.md) | Converting a numeric value to a text line with a specified accuracy |
| [EnumToString](enumtostring.md) | Converting an enumeration value of any type to string |
| [NormalizeDouble](normalizedouble.md) | Rounding of a floating point number to a specified accuracy |
| [StringToDouble](stringtodouble.md) | Converting a string containing a symbol representation of number into number of double type |
| [StringToInteger](stringtointeger.md) | Converting a string containing a symbol representation of number into number of long type |
| [StringToTime](stringtotime.md) | Converting a string containing time or date in "yyyy.mm.dd [hh:mi]" format into datetime type |
| [TimeToString](timetostring.md) | Converting a value containing time in seconds elapsed since 01.01.1970 into a string of "yyyy.mm.dd hh:mi" format |
| [IntegerToString](integertostring.md) | Converting int into a string of preset length |
| [ShortToString](shorttostring.md) | Converting symbol code (unicode) into one-symbol string |
| [ShortArrayToString](shortarraytostring.md) | Copying array part into a string |
| [StringToShortArray](stringtoshortarray.md) | Symbol-wise copying a string to a selected part of array of ushort type |
| [CharArrayToString](chararraytostring.md) | Converting symbol code (ansi) into one-symbol array |
| [StringToCharArray](stringtochararray.md) | Symbol-wise copying a string converted from Unicode to ANSI, to a selected place of array of uchar type |
| [CharArrayToStruct](chararraytostruct.md) | Copy uchar type array to [POD structure](classes.md#simple_structure) |
| [StructToCharArray](structtochararray.md) | Copy [POD structure](classes.md#simple_structure) to uchar type array |
| [ColorToARGB](colortoargb.md) | Converting color type to uint type to receive ARGB representation of the color. |
| [ColorToPRGB](colortoprgb.md) | Converts the type [color](color.md) in type [uint](integertypes.md#uint) to get premultiplied ARGB representation of color - PRGB. |
| [ColorToString](colortostring.md) | Converting color value into string as "R,G,B" |
| [StringToColor](stringtocolor.md) | Converting "R,G,B" string or string with color name into color type value |
| [StringFormat](stringformat.md) | Converting number into string according to preset format |

See also

[Use of a Codepage](codepageusage.md)