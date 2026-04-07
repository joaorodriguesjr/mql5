ParamDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Custom indicators](customindicator.md) / ParamDouble

[![Previous](previous.png)](cicustomparamlong.md) 
[![Next](next.png)](cicustomparamstring.md)

ParamDouble

Gets the value of specified parameter of double type.

```
double  ParamDouble(
   int  index      // index
   ) const
```

Parameters

index

[in]  Parameter index.

Return Value

The value of specified parameter of double type, used in creation of the indicator.

Note

If the parameter index is invalid or the parameter type is not of double type, it returns [EMPTY\_VALUE](otherconstants.md).