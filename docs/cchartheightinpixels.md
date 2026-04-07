HeightInPixels



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / HeightInPixels

[![Previous](previous.png)](cchartwidthinpixels.md) 
[![Next](next.png)](cchartpricemin.md)

HeightInPixels

Gets window height in pixels.

```
int  HeightInPixels(
   int  num      // subwindow
   ) const
```

Parameters

num

[in]  Checked subwindow number (0 means main window).

Return Value

Window height in pixels of the chart assigned to the class instance. If there is no chart assigned, it returns 0.