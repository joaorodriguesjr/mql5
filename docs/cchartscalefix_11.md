ScaleFix\_11



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ScaleFix\_11

[![Previous](previous.png)](cchartscalefix.md) 
[![Next](next.png)](cchartfixedmax.md)

ScaleFix\_11 (Get Method)

Gets the value of "ScaleFix\_11" property (chart scale is 1:1, or not).

```
bool  ScaleFix_11() const
```

Return Value

Value of "ScaleFix\_11" property of the chart assigned to the class instance. If there is no chart assigned, it returns false.

ScaleFix\_11 (Set Method)

Sets new value for "ScaleFix\_11" property.

```
bool  ScaleFix_11(
   string  scale_11      // property value
   )
```

Parameters

scale\_11

[in]  New value for "ScaleFix\_11" property.

Return Value

true - successful, false - cannot change the property.