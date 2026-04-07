IndicatorsTotal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / IndicatorsTotal

[![Previous](previous.png)](cchartindicatordelete.md) 
[![Next](next.png)](cchartindicatorname.md)

IndicatorsTotal

Returns the number of all indicators applied to the specified chart window.

```
int  IndicatorsTotal(
   long   chart_id,  // chart identifier
   int    sub_win    // number of the subwindow
   );
```

Parameters

chart\_id

[in]  Chart identifier. 0 denotes the main chart.

sub\_win

[in]  Number of the chart subwindow. 0 denotes the main chart window.

Return Value

The number of indicators in the specified chart window. To get [error](errorcodes.md) details, use the [GetLastError()](getlasterror.md) function.

Note

The function allows going searching through all the indicators attached to the chart. The number of all the windows of the chart can be obtained from the [CHART\_WINDOWS\_TOTAL](enum_chart_property.md#enum_chart_property_integer) property using the [GetInteger()](cchartgetinteger.md) function.

See also

[IndicatorAdd()](cchartindicatoradd.md), [IndicatorDelete()](cchartindicatordelete.md), [IndicatorsTotal()](cchartindicatorstotal.md), [iCustom()](icustom.md), [IndicatorCreate()](indicatorcreate.md), [IndicatorSetString()](indicatorsetstring.md).