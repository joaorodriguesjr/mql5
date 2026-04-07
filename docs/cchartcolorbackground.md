ColorBackground



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorBackground

[![Previous](previous.png)](cchartshowpricescale.md) 
[![Next](next.png)](cchartcolorforeground.md)

ColorBackground (Get Method)

Gets the value of "ColorBackground" property (background color of the chart).

```
color  ColorBackground() const
```

Return Value

Value of "ColorBackground" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorBackground (Set Method)

Sets new value for "ColorBackground" property.

```
bool  ColorBackground(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New background color.

Return Value

true - successful, false - cannot change the color.