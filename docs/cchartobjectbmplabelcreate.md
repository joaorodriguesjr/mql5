Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectBmpLabel](cchartobjectbmplabel.md) / Create

[![Previous](previous.png)](cchartobjectbmplabel.md) 
[![Next](next.png)](cchartobjectbmplabelx_distance.md)

Create

Creates "BmpLabel" graphical object.

```
bool  Create(
   long    chart_id,     // chart identifier
   string  name,         // object name
   int     window,       // chart window
   int     X,            // X coordinate
   int     Y             // Y coordinate
   )
```

Parameters

chart\_id

[in]  Chart identifier (0 current chart).

name

[in]  A unique name of the object to create.

window

[in]  Chart window number (0 main window).

X

[in]  X coordinate.

Y

[in]  Y coordinate.

Return Value

true - successful, false - error.