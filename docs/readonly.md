ReadOnly



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectEdit](cchartobjectedit.md) / ReadOnly

[![Previous](previous.png)](cchartobjecteditbordercolor.md) 
[![Next](next.png)](cchartobjecteditangle.md)

ReadOnly (Get Method)

Gets the value of "Read Only" property.

```
bool  ReadOnly() const
```

Return Value

Value of "Read Only" property of the object assigned to the class instance. If there is no object assigned, it returns false.

ReadOnly (Set Method)

Sets the value for "Read Only" property.

```
bool  ReadOnly(
   const  bool  flag      // new property value
   )
```

Parameters

flag

[in]  New value for "Read Only" property (true means text editing is disabled).

Return Value

true - success, false - cannot change the property.