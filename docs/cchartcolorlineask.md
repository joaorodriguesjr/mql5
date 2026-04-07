ColorLineAsk



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorLineAsk

[![Previous](previous.png)](cchartcolorlinebid.md) 
[![Next](next.png)](cchartcolorlinelast.md)

ColorLineAsk (Get Method)

Gets the value of "ColorLineAsk" property (color of Ask line).

```
color  ColorLineAsk() const
```

Return Value

Value of "ColorLineAsk" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorLineAsk (Set Method)

Sets new value for "ColorLineAsk" property.

```
bool  ColorLineAsk(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New color for Ask line.

Return Value

true - successful, false - cannot change the color.