Navigate



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / Navigate

[![Previous](previous.png)](cchartindicatorname.md) 
[![Next](next.png)](cchartsymbol.md)

Navigate

Shifts the chart.

```
bool  Navigate(
   ENUM_CHART_POSITION  position,     // position
   int                  shift=0       // shift
   )
```

Parameters

position

[in]  Chart position (from [ENUM\_CHART\_POSITION](enum_chart_position.md) enumeration), relative to which a shift is performed.

shift=0

[in]  Number of bars to shift.

Return Value

true - successful, false - cannot shift the chart.