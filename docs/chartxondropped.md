ChartXOnDropped



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartXOnDropped

[![Previous](previous.png)](charttimeondropped.md) 
[![Next](next.png)](chartyondropped.md)

ChartXOnDropped

Returns the X coordinate of the chart point the Expert Advisor or script has been dropped to.

```
int  ChartXOnDropped();
```

Return Value

The X coordinate value.

Note

X axis direction from left to right.

Example:

```
   int X=ChartXOnDropped();
   int Y=ChartYOnDropped();
   Print("(X,Y) = ("+X+","+Y+")");
```

See also

[ChartWindowOnDropped](chartwindowondropped.md), [ChartPriceOnDropped](chartpriceondropped.md), [ChartTimeOnDropped](charttimeondropped.md)