IndicatorAdd



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / IndicatorAdd

[![Previous](previous.png)](ccharteventobjectdelete.md) 
[![Next](next.png)](cchartindicatordelete.md)

IndicatorAdd

Adds an indicator with the specified handle into a specified chart window.

```
bool  IndicatorAdd(
   int   sub_win         // number of the subwindow
   int   handle          // handle of the indicator
   );
```

Parameters

sub\_win

[in]  The number of the chart subwindow. 0 means the main chart window. if the number of a non-existing window is specified, a new window will be created.

handle

[in]  The handle of the indicator.

Return Value

The function returns true in case of success, otherwise it returns false. In order to obtain information about the [error](errorcodes.md), call the [GetLastError()](getlasterror.md) function.

See also

[IndicatorDelete()](cchartindicatordelete.md), [IndicatorsTotal()](cchartindicatorstotal.md), [IndicatorName()](cchartindicatorname.md).