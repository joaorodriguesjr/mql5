PriceMin



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / PriceMin

[![Previous](previous.png)](cchartheightinpixels.md) 
[![Next](next.png)](cchartpricemax.md)

PriceMin

Gets window minimal price.

```
double  PriceMin(
   int  num      // subwindow
   ) const
```

Parameters

num

[in]  Subwindow number (0 means main window).

Return Value

Window minimal price value of the chart assigned to the class instance. If there is not chart assigned, it returns [EMPTY\_VALUE](otherconstants.md).