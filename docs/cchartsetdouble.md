SetDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / SetDouble

[![Previous](previous.png)](cchartgetdouble.md) 
[![Next](next.png)](cchartgetstring.md)

SetDouble

Sets new value for the chart property of the double type.

```
bool  SetDouble(
   ENUM_CHART_PROPERTY_DOUBLE  prop_id,     // property identifier
   double                      value        // new value
   )
```

Parameters

prop\_id

[in]  Chart property identifier (from [ENUM\_CHART\_PROPERTY\_DOUBLE](enum_chart_property.md#enum_chart_property_double) enumeration).

value

[in]  New value for the property.

Return Value

true - successful, false - cannot change the double property.