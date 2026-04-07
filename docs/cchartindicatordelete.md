IndicatorDelete



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / IndicatorDelete

[![Previous](previous.png)](cchartindicatoradd.md) 
[![Next](next.png)](cchartindicatorstotal.md)

IndicatorDelete

Removes an indicator with a specified name from the specified chart window.

```
bool  IndicatorDelete(
   int            sub_win       // number of the subwindow
   const string   name          // short name of the indicator
   );
```

Parameters

sub\_win

[in]  Number of the chart subwindow. 0 denotes the main chart subwindow.

const name

[in]  The short name of the indicator which is set in the [INDICATOR\_SHORTNAME](customindicatorproperties.md#enum_customind_property_string) property with the [IndicatorSetString()](indicatorsetstring.md) function. To get the short name of an indicator, use the [IndicatorName()](cchartindicatorname.md) function.

Return Value

Returns true in case of successful deletion of the indicator. Otherwise it returns false. To get [error](errorcodes.md) details, use the [GetLastError()](getlasterror.md) function.

Note

If two indicators with identical short names exist in the chart subwindow, the first one in a row will be deleted.

If other indicators on this chart are based on the values of the indicator that is being deleted, such indicators will also be deleted.

Do not confuse the indicator short name and the file name that is specified when creating an indicator using functions [iCustom()](icustom.md) and [IndicatorCreate()](indicatorcreate.md). If the short name of an indicator is not set explicitly, then the name of the file containing the source code of the indicator will be specified during compilation.

Deletion of an indicator from a chart does not mean that its calculation part will be deleted from the terminal memory. To release the indicator handle, use the [IndicatorRelease()](indicatorrelease.md) function.

The indicator's short name should be formed correctly. It will be written to the [INDICATOR\_SHORTNAME](customindicatorproperties.md#enum_customind_property_string) property using the [IndicatorSetString()](indicatorsetstring.md) function. It is recommended that the short name should contain values of all the input parameters of the indicator, because the indicator to be deleted from the chart by the [IndicatorDelete()](cchartindicatordelete.md) function is identified by the short name.

See also

[IndicatorAdd()](cchartindicatoradd.md), [IndicatorsTotal()](cchartindicatorstotal.md), [IndicatorName()](cchartindicatorname.md), [iCustom()](icustom.md), [IndicatorCreate()](indicatorcreate.md), [IndicatorSetString()](indicatorsetstring.md).