BackColor



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectRectLabel](cchartobjectrectlabel.md) / BackColor

[![Previous](previous.png)](cchartobjectrectlabely_size.md) 
[![Next](next.png)](cchartobjectrectlabelangle.md)

BackColor

Gets the background color property value.

```
color  BackColor() const
```

Return Value

Background color property value of the object assigned to the class instance. If there is no object assigned, it returns 0.

 

BackColor

Sets the background color property value.

```
bool  BackColor(
   color  new_color      // property value
   )
```

Parameters

new\_color

[in]  New background color property value.

Return Value

true - successful, false - cannot change the property.