Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Line Objects](obj_lines.md)  /  [CChartObjectVLine](cchartobjectvline.md) / Create

[![Previous](previous.png)](cchartobjectvline.md) 
[![Next](next.png)](cchartobjectvlinetype.md)

Create

Creates "Vertical Line" graphical object.

```
bool  Create(
   long      chart_id,     // chart identifier
   string    name,         // object name
   int       window,       // chart window
   datetime  time          // time coordinate
   )
```

Parameters

chart\_id

[in]  Chart identifier (0 current chart).

name

[in]  A unique name of the object to create.

window

[in]  Chart window number (0 main window).

time

[in]  Time coordinate of the anchor point.

Return Value

true - successful, false - error.