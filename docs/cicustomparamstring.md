ParamString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Custom indicators](customindicator.md) / ParamString

[![Previous](previous.png)](cicustomparamdouble.md) 
[![Next](next.png)](cicustomtype.md)

ParamString

Gets the value of specified parameter of string type.

```
string  ParamString(
   int  index      // index
   ) const
```

Parameters

index

[in]  Parameter index.

Return Value

The value of specified string parameter, used in creation of the indicator.

Note

If the number is invalid or the parameter is not of string type, it returns an empty string.