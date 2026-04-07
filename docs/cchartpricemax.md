PriceMax



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / PriceMax

[![Previous](previous.png)](cchartpricemin.md) 
[![Next](next.png)](cchartattach.md)

PriceMax

Gets window maximal price.

```
double  PriceMax(
   int  num      // subwindow
   ) const
```

Parameters

num

[in]  Subwindow number (0 means main window).

Return Value

Window maximal price value of the chart assigned to the class instance. If there is not chart assigned, it returns [EMPTY\_VALUE](otherconstants.md).