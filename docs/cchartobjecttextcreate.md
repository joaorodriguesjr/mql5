Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectText](cchartobjecttext.md) / Create

[![Previous](previous.png)](cchartobjecttext.md) 
[![Next](next.png)](cchartobjecttextangle.md)

Create

Creates "Text" graphical object.

```
bool  Create(
   long      chart_id,     // chart identifier
   string    name,         // object name
   int       window,       // chart window
   datetime  time,         // time coordinate
   double    price         // price coordinate
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

price

[in]  Price coordinate of the anchor point.

Return Value

true - successful, false - error.