Scale



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectSubChart](cchartobjectsubchart.md) / Scale

[![Previous](previous.png)](cchartobjectsubchartperiod.md) 
[![Next](next.png)](cchartobjectsubchartdatescale.md)

Scale (Get Method)

Gets the value of "Scale" property.

```
double  Scale() const
```

Return Value

Value of "Scale" property of the object assigned to the class instance. If there is no object assigned, it returns [EMPTY\_VALUE](otherconstants.md).

Scale (Set Method)

Sets new value for "Scale" property.

```
bool  Scale(
   double  scale      // property value
   )
```

Parameters

scale

[in]  New value for "Scale" property.

Return Value

true - successful, false - cannot change the property.