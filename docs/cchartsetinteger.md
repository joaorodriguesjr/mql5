SetInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / SetInteger

[![Previous](previous.png)](cchartgetinteger.md) 
[![Next](next.png)](cchartgetdouble.md)

SetInteger

Sets new value for the property of the integer type.

```
bool  SetInteger(
   ENUM_CHART_PROPERTY_INTEGER  prop_id,     // property identifier
   long                         value        // value
   )
```

Parameters

prop\_id

[in]  Chart property identifier (from [ENUM\_CHART\_PROPERTY\_INTEGER](enum_chart_property.md#enum_chart_property_integer) enumeration).

value

[in]  New value of the property.

Return Value

true - successful, false - cannot change the integer property.