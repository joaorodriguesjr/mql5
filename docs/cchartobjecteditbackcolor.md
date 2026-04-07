BackColor



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectEdit](cchartobjectedit.md) / BackColor

[![Previous](previous.png)](cchartobjectedity_size.md) 
[![Next](next.png)](cchartobjecteditbordercolor.md)

BackColor (Get Method)

Gets the value of "BackColor" property.

```
color  BackColor() const
```

Return Value

Value of "BackColor" property of the object assigned to the class instance. If there is no object assigned, it returns CLR\_NONE.

BackColor (Set Method)

Sets the value for "BackColor" property.

```
bool  BackColor(
   color  new_color      // property value
   )
```

Parameters

new\_color

[in]  New value for "BackColor" property.

Return Value

true - success, false - cannot change the property.