ChartTimeOnDropped



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartTimeOnDropped

[![Previous](previous.png)](chartpriceondropped.md) 
[![Next](next.png)](chartxondropped.md)

ChartTimeOnDropped

Returns the time coordinate corresponding to the chart point the Expert Advisor or script has been dropped to.

```
datetime  ChartTimeOnDropped();
```

Return Value

Value of [datetime](datetime.md) type.

Example:

```
   datetime t=ChartTimeOnDropped();
   Print("Script was dropped on the "+t);
```

See also

[ChartXOnDropped](chartxondropped.md), [ChartYOnDropped](chartyondropped.md)