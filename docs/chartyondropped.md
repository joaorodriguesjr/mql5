ChartYOnDropped



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartYOnDropped

[![Previous](previous.png)](chartxondropped.md) 
[![Next](next.png)](chartsetsymbolperiod.md)

ChartYOnDropped

Returns the Y coordinateof the chart point the Expert Advisor or script has been dropped to.

```
int  ChartYOnDropped();
```

Return Value

The Y coordinate value.

Note

Y axis direction from top to bottom.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get and print the X and Y coordinates of the chart point the script was dropped into using the mouse
   int x=ChartXOnDropped();
   int y=ChartYOnDropped();
   PrintFormat("Script dropped to coordinates X = %d, Y = %d", x, y);
   /*
   result:
   Script dropped to coordinates X = 429, Y = 114
   */
  }
```

See also

[ChartWindowOnDropped](chartwindowondropped.md), [ChartPriceOnDropped](chartpriceondropped.md), [ChartTimeOnDropped](charttimeondropped.md)