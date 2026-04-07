PlotIndexSetDouble



[MQL5 Reference](index.md)  /  [Custom Indicators](customind.md) / PlotIndexSetDouble

[![Previous](previous.png)](indicatorsetstring.md) 
[![Next](next.png)](plotindexsetinteger.md)

PlotIndexSetDouble

The function sets the value of the corresponding property of the corresponding indicator line. The indicator property must be of the double type.

```
bool  PlotIndexSetDouble(
   int     plot_index,     // plotting style index
   int     prop_id,        // property identifier
   double  prop_value      // value to be set
   );
```

Parameters

plot\_index

[in]  Index of the [graphical plotting](drawstyles.md#enum_draw_type)

prop\_id

[in] The value can be one of the values of the [ENUM\_PLOT\_PROPERTY\_DOUBLE](drawstyles.md#enum_plot_property_double) enumeration.

prop\_value

[in]  The value of the property.

Return Value

If successful, returns [true](boolconst.md), otherwise [false](boolconst.md).