Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Channel Objects](obj_channels.md)  /  [CChartObjectStdDevChannel](cchartobjectstddevchannel.md) / Create

[![Previous](previous.png)](cchartobjectstddevchannel.md) 
[![Next](next.png)](cchartobjectstddevchanneldeviations.md)

Create

Creates "Standard Deviation Channel" graphical object.

```
bool  Create(
   long      chart_id,      // chart identifier
   string    name,          // object name
   int       window,        // chart window
   datetime  time1,         // first time coordinate
   datetime  time2,         // second time coordinate
   double    deviation      // deviation
   )
```

Parameters

chart\_id

[in]  Chart identifier (0 current chart).

name

[in]  A unique name of the object to create.

window

[in]  Chart window number (0 main window).

time1

[in]  Time coordinate of the first anchor point.

time2

[in]  Time coordinate of the second anchor point.

deviation

[in]  Numerical value for "Deviation" property.

Return Value

true - successful, false - error.