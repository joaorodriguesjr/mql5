ChartWindowOnDropped



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartWindowOnDropped

[![Previous](previous.png)](chartindicatorstotal.md) 
[![Next](next.png)](chartpriceondropped.md)

ChartWindowOnDropped

Returns the number (index) of the chart subwindow the Expert Advisor or script has been dropped to. 0 means the main chart window.

```
int  ChartWindowOnDropped();
```

Return Value

Value of [int](integertypes.md) type.

Example:

```
   int myWindow=ChartWindowOnDropped();
   int windowsTotal=ChartGetInteger(0,CHART_WINDOWS_TOTAL);
   Print("Script is running on the window #"+myWindow+
         ". Total windows on the chart "+ChartSymbol()+":",windowsTotal);
```

See also

[ChartPriceOnDropped](chartpriceondropped.md), [ChartTimeOnDropped](charttimeondropped.md), [ChartXOnDropped](chartxondropped.md), [ChartYOnDropped](chartyondropped.md)