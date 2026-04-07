SeriesAdd



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CHistogramChart](chistogramchart.md) / SeriesAdd

[![Previous](previous.png)](chistogramchartcreate.md) 
[![Next](next.png)](chistogramchartseriesinsert.md)

SeriesAdd

Adds a new data series.

```
 bool  SeriesAdd(
   const double&  value[],  // values
   const string  descr,     // label
   const uint    clr,       // color
   )
```

Parameters

value[]

[in] Data series.

descr

[in] Series label.

clr

[in] Series display color.

Return Value

true if successful, otherwise false.