ChartPriceOnDropped



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartPriceOnDropped

[![Previous](previous.png)](chartwindowondropped.md) 
[![Next](next.png)](charttimeondropped.md)

ChartPriceOnDropped

Returns the price coordinate corresponding to the chart point the Expert Advisor or script has been dropped to.

```
double  ChartPriceOnDropped();
```

Return Value

Value of [double](double.md) type.

Example:

```
   double p=ChartPriceOnDropped();
   Print("ChartPriceOnDropped() = ",p);
```

See also

[ChartXOnDropped](chartxondropped.md), [ChartYOnDropped](chartyondropped.md)