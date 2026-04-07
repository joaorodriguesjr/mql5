PlotIndexSetString



[MQL5 Reference](index.md)  /  [Custom Indicators](customind.md) / PlotIndexSetString

[![Previous](previous.png)](plotindexsetinteger.md) 
[![Next](next.png)](plotindexgetinteger.md)

PlotIndexSetString

The function sets the value of the corresponding property of the corresponding indicator line. The indicator property must be of the string type.

```
bool  PlotIndexSetString(
   int     plot_index,     // plotting style index
   int     prop_id,        // property identifier
   string  prop_value      // value to be set
   );
```

Parameters

plot\_index

[in]  Index of [graphical plot](drawstyles.md#enum_draw_type)

prop\_id

[in] The value can be one of the values of the [ENUM\_PLOT\_PROPERTY\_STRING](drawstyles.md#enum_plot_property_string) enumeration.

prop\_value

[in]  The value of the property.

Return Value

If successful, returns [true](boolconst.md), otherwise [false](boolconst.md).