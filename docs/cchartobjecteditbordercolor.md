BorderColor



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectEdit](cchartobjectedit.md) / BorderColor

[![Previous](previous.png)](cchartobjecteditbackcolor.md) 
[![Next](next.png)](readonly.md)

BorderColor (Get Method)

Gets the value of "Border Color" property.

```
color  BorderColor() const
```

Return Value

Value of "Border Color" property of the object assigned to the class instance. If there is no object assigned, it returns CLR\_NONE.

BorderColor (Set Method)

Sets new value for "Border Color" property.

```
bool  BorderColor(
   color  new_color      // new property value
   )
```

Parameters

new\_color

[in]  New value for "Border Color" property.

Return Value

true - success, false - cannot change the property.