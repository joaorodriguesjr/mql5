IndicatorName



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / IndicatorName

[![Previous](previous.png)](cchartindicatorstotal.md) 
[![Next](next.png)](cchartnavigate.md)

IndicatorName

Returns the short name of the indicator by the index in the indicators list on the specified chart window.

```
string  IndicatorName(
   int   sub_win     // number of the subwindow
   int   index       // index of the indicator in the list of indicators added to the chat subwindow
   );
```

Parameters

sub\_win

[in]  Number of the chart subwindow. 0 denotes the main chart window.

index

[in]  Index of the indicator in the list of indicators. The numeration of indicators start with zero, i.e. the first indicator in the list has the 0 index. To obtain the number of indicators in the list, use the [IndicatorsTotal()](cchartindicatorstotal.md) function.

Return Value

The short name of the indicator which is set in the [INDICATOR\_SHORTNAME](customindicatorproperties.md#enum_customind_property_string) property with the [IndicatorSetString()](indicatorsetstring.md) function. To get [error](errorcodes.md) details, use the [GetLastError()](getlasterror.md) function.

Note

Do not confuse the indicator short name and the file name that is specified when creating an indicator using functions [iCustom()](icustom.md) and [IndicatorCreate()](indicatorcreate.md). If the short name of an indicator is not set explicitly, then the name of the file containing the source code of the indicator will be specified during compilation.

The indicator's short name should be formed correctly. It will be written to the [INDICATOR\_SHORTNAME](customindicatorproperties.md#enum_customind_property_string) property using the [IndicatorSetString()](indicatorsetstring.md) function. It is recommended that the short name should contain values of all the input parameters of the indicator, because the indicator to be deleted from the chart by the [IndicatorDelete()](cchartindicatordelete.md) function is identified by the short name.

See also

[IndicatorAdd()](cchartindicatoradd.md), [IndicatorDelete](cchartindicatordelete.md), [IndicatorsTotal](cchartindicatorstotal.md), [iCustom()](icustom.md), [IndicatorCreate()](indicatorcreate.md), [IndicatorSetString()](indicatorsetstring.md).