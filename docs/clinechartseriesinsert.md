SeriesInsert



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CLineChart](clinechart.md) / SeriesInsert

[![Previous](previous.png)](clinechartseriesadd.md) 
[![Next](next.png)](clinechartseriesupdate.md)

SeriesInsert

Inserts data series to the chart.

```
 bool  SeriesInsert(
   const uint     pos,       // index
   const double&  value[],   // values
   const string   descr,     // label
   const uint     clr,       // color
   )
```

Parameters

pos

[in] Index for insertion.

value[]

[in] Dara series. 

descr

[in] Series label. 

clr

[in] Series display color. 

Return Value

true if successful, otherwise false.