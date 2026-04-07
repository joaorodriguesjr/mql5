ColorLineBid



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorLineBid

[![Previous](previous.png)](cchartcolorvolumes.md) 
[![Next](next.png)](cchartcolorlineask.md)

ColorLineBid (Get Method)

Gets the value of "ColorLineBid" property (color of Bid line).

```
color  ColorLineBid() const
```

Return Value

Value of "ColorLineBid" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorLineBid (Set Method)

Sets new value for "ColorLineBid" property.

```
bool  ColorLineBid(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New color for Bid line.

Return Value

true - successful, false - cannot change the color.