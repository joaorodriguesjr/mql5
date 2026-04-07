PointsPerBar



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / PointsPerBar

[![Previous](previous.png)](cchartfixedmin.md) 
[![Next](next.png)](cchartscaleppb.md)

PointsPerBar (Get Method)

Gets the value of "PointsPerBar" property (in points per bar).

```
double  PointsPerBar() const
```

Return Value

Value of "PointsPerBar" property of the chart assigned to the class instance. If there is no chart assigned, it returns [EMPTY\_VALUE](otherconstants.md).

PointsPerBar (Set Method)

Sets new value for "PointsPerBar" property.

```
bool  PointsPerBar(
   double  ppb      // scale
   )
```

Parameters

ppb

[in]  New scale (in points per bar).

Return Value

true - successful, false - cannot change the scale.