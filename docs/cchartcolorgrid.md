ColorGrid



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorGrid

[![Previous](previous.png)](cchartcolorforeground.md) 
[![Next](next.png)](cchartcolorbarup.md)

ColorGrid (Get Method)

Gets the value of "ColorGrid" property (color of the grid).

```
color  ColorGrid() const
```

Return Value

Value of "ColorGrid" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorGrid (Set Method)

Sets new value for "ColorGrid" property.

```
bool  ColorGrid(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New grid color.

Return Value

true - successful, false - cannot change the color.