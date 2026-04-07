ColorStopLevels



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorStopLevels

[![Previous](previous.png)](cchartcolorlinelast.md) 
[![Next](next.png)](cchartvisiblebars.md)

ColorStopLevels (Get Method)

Gets the value of "ColorStopLevels" property (color of the SL and TP levels).

```
color  ColorStopLevels() const
```

Return Value

Value of "ColorStopLevels" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorStopLevels (Set Method)

Sets new value for "ColorStopLevels" property.

```
bool  ColorStopLevels(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New color of the Stop Loss and Take Profit price levels.

Return Value

true - successful, false - cannot change the color.