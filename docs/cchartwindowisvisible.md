WindowIsVisible



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / WindowIsVisible

[![Previous](previous.png)](cchartwindowstotal.md) 
[![Next](next.png)](cchartwindowhandle.md)

WindowIsVisible

Gets visibility flag of the specified chart subwindow.

```
bool  WindowIsVisible(
   int  num      // subwindow
   ) const
```

Parameters

num

[in]  Subwindow number (0 means main window).

Return Value

Returns visibility flag of the specified chart subwindow assigned to the chart instance.  If there is no chart assigned, it returns false.