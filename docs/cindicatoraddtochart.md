AddToChart



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / AddToChart

[![Previous](previous.png)](cindicatorvolumedescription.md) 
[![Next](next.png)](cindicatordeletefromchart.md)

AddToChart

Adds the indicator to the chart.

```
bool  AddToChart(
   const long  chart,     // chart ID
   const int  subwin      // subwindow index
   )
```

Parameters

chart

[in]  Chart ID.

subwin

[in]  Chart subwindow index.

Return Value

true successful, false - cannot add the indicator to the chart.