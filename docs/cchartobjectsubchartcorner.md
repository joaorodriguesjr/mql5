Corner



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectSubChart](cchartobjectsubchart.md) / Corner

[![Previous](previous.png)](cchartobjectsubcharty_distance.md) 
[![Next](next.png)](cchartobjectsubchartx_size.md)

Corner (Get Method)

Gets the value of "Corner" property.

```
ENUM_BASE_CORNER Corner() const
```

Return Value

Value of "Corner" property of the object assigned to the class instance. If there is no object assigned, it returns WRONG\_VALUE.

Corner (Set Method)

Sets new value for "Corner" property.

```
bool  Corner(
   ENUM_BASE_CORNER  corner      // property value
   )
```

Parameters

corner

[in]  New value for "Corner" property.

Return Value

true - successful, false - cannot change the property.