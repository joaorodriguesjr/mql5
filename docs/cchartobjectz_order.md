Z\_Order



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [CChartObject](cchartobject.md) / Z\_Order

[![Previous](previous.png)](cchartobjecttimeframes.md) 
[![Next](next.png)](cchartobjectcreatetime.md)

Z\_Order (Get Method)

Gets the graphical object priority for receiving an event of mouse clicking on a chart ([CHARTEVENT\_CLICK](enum_chartevents.md)).

```
long  Z_Order() const
```

Return Value

Priority of a graphical object, attached to the class instance. If there is no object attached, it returns 0.

Z\_Order (Set Method)

Sets the graphical object priority for receiving an event of mouse clicking on a chart ([CHARTEVENT\_CLICK](enum_chartevents.md)).

```
bool  Z_Order(
   long  value      // graphical object priority
   )
```

Parameters

value

[in]  New value of priority of a graphical object for receiving the event [CHARTEVENT\_CLICK](enum_chartevents.md).

Return Value

true - success, false - cannot change the priority.

Note

Z\_Order property manages a priority when handling clicks on graphical objects. By setting the value greater than 0 (default value), you can increase the object priority when handling mouse clicks.