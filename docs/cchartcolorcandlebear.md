ColorCandleBear



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ColorCandleBear

[![Previous](previous.png)](cchartcolorcandlebull.md) 
[![Next](next.png)](cchartcolorchartline.md)

ColorCandleBear (Get Method)

Gets the value of "ColorCandleBear" property (body color of the bearish candle).

```
color  ColorCandleBear() const
```

Return Value

Value of "ColorCandleBear" property of the chart assigned to the class instance. If there is no chart assigned, it returns [CLR\_NONE](otherconstants.md).

ColorCandleBear (Set Method)

Sets new value for "ColorCandleBear" property.

```
bool  ColorCandleBear(
   color  new_color      // color
   )
```

Parameters

new\_color

[in]  New color of the bearish candle body.

Return Value

true - successful, false - cannot change the color.