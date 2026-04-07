SetString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / SetString

[![Previous](previous.png)](cchartgetstring.md) 
[![Next](next.png)](cchartsetsymbolperiod.md)

SetString

Sets new value for the chart property of the string type.

```
bool  SetString(
   ENUM_CHART_PROPERTY_STRING  prop_id,     // property identifier
   string                      value        // value
   )
```

Parameters

prop\_id

[in]  Chart property identifier (from [ENUM\_CHART\_PROPERTY\_STRING](enum_chart_property.md#enum_chart_property_string) enumeration).

value

[in]  New value for the property.

Return Value

true - successful, false - cannot change the string property.