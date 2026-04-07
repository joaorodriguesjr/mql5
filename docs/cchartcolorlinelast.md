ColorLineLast



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorLineLast

[![Previous](previous.png)](cchartcolorlineask.md) 
[![Next](next.png)](cchartcolorstoplevels.md)

ColorLineLast (Get Method)

Gets the value of "ColorLineLast" property (color of the last deal price line).

```
color  ColorLineLast() const
```

Return Value

Value of "ColorLineLast" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorLineLast (Set Method)

Sets new value for "ColorLineLast" property.

```
bool  ColorLineLast(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New color of the last deal price line.

Return Value

true - successful, false - cannot change the color.