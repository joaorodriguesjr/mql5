DeleteFromChart



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / DeleteFromChart

[![Previous](previous.png)](cindicatoraddtochart.md) 
[![Next](next.png)](cindicators2.md)

DeleteFromChart

Deletes the indicator from the chart.

```
bool  DeleteFromChart(
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

true successful, false - cannot remove the indicator from the chart.