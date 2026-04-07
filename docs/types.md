Data Types



[MQL5 Reference](index.md)  /  [Language Basics](basis.md) / Data Types

[![Previous](previous.png)](reserved.md) 
[![Next](next.png)](integer.md)

Data Types

Any program operates with data. Data can be of different types depending on their purposes. For example, integer data are used to access to array components. Price data belong to those of double precision with floating point. This is related to the fact that no special data type for price data is provided in MQL5.

Data of different types are processed with different rates. Integer data are processed at the fastest. To process the double precision data, a special co-processor is used. However, because of complexity of internal representation of data with floating point, they are processed slower than the integer ones.

String data are processed at the longest because of dynamic computer memory allocation/reallocation.

The basic data types are:

* integers ([char](integertypes.md), [short](integertypes.md), [int](integertypes.md), [long](integertypes.md), [uchar](integertypes.md), [ushort](integertypes.md), [uint](integertypes.md), [ulong](integertypes.md));
* logical ([bool](boolconst.md));
* [literals](symbolconstants.md) (ushort);
* strings ([string](stringconst.md));
* floating-point numbers ([double](double.md), [float](double.md));
* color ([color](color.md));
* date and time ([datetime](datetime.md));
* enumerations ([enum](enumeration.md)).

Complex data types are:

* [structures](classes.md);
* [classes](classes.md#class).

In terms of [OOP](oop.md) complex data types are called abstract data types.

The color and datetime types make sense only to facilitate visualization and input of parameters defined from outside - from the table of Expert Advisor or custom indicator properties (the [Inputs](inputvariables.md) tab). Data of color and datetime types are represented as integers. Integer types and floating-point types are called arithmetic (numeric) types.

Only implicit [type casting](casting.md) is used in [expressions](operexpression.md), unless the explicit casting is specified.

See also

[Typecasting](casting.md)