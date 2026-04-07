ParamType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Custom indicators](customindicator.md) / ParamType

[![Previous](previous.png)](cicustomnumparams.md) 
[![Next](next.png)](cicustomparamlong.md)

ParamType

Gets a type of the parameter.

```
ENUM_DATATYPE  ParamType(
   int  index      // index
   ) const
```

Parameters

index

[in]  Parameter index.

Return Value

Returns the data type of the specified parameter, used in indicator creation.

Note

If parameter index is invalid, it returns [WRONG\_VALUE](otherconstants.md).