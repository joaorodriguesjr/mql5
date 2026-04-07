ColorBarUp



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorBarUp

[![Previous](previous.png)](cchartcolorgrid.md) 
[![Next](next.png)](cchartcolorbardown.md)

ColorBarUp (Get Method)

Gets the value of "ColorBarUp" property (color for bullish bars, their shadow, and candle body outlines).

```
color  ColorBarUp() const
```

Return Value

Value of "ColorBarUp" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorBarUp (Set Method)

Sets new value for "ColorBarUp" property.

```
bool  ColorBarUp(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New color for bullish bars, their shadow and candle body outlines.

Return Value

true - successful, false - cannot change the color.