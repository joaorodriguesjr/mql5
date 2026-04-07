Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Elliott Tools](obj_elliott.md)  /  [CChartObjectElliottWave3](cchartobjectelliottwave3.md) / Create

[![Previous](previous.png)](cchartobjectelliottwave3.md) 
[![Next](next.png)](cchartobjectelliottwave3degree.md)

Create

Creates "Correcting Wave" graphical object.

```
bool  Create(
   long      chart_id,     // chart identifier
   string    name,         // object name
   int       window,       // chart window 
   datetime  time1,        // first time coordinate
   double    price1,       // first price coordinate
   datetime  time2,        // second time coordinate
   double    price2,       // second price coordinate
   datetime  time3,        // third time coordinate
   double    price3        // third price coordinate
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

price1

[in]  Price coordinate of the first anchor point.

time2

[in]  Time coordinate of the second anchor point.

price2

[in]  Price coordinate of the second anchor point.

time3

[in]  Time coordinate of the third anchor point.

price3

[in]  Time coordinate of the third anchor point.

Return Value

true - successful, false - error.