Accumulative



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CChartCanvas](cchartcanvas.md) / Accumulative

[![Previous](previous.png)](cchartcanvaslegendalignment.md) 
[![Next](next.png)](cchartcanvasvscaleparams.md)

Accumulative

Sets the value accumulation flag for the series.                                           

```
 void  Accumulative(
   const bool  flag=true,  // flag value
   )
```

Parameters

flag=true

[in] Flag value:

* true the current value of the series is replaced by the sum of all previous values.
* false the standard mode for drawing series.