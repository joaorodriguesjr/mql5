TextAlign



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectEdit](cchartobjectedit.md) / TextAlign

[![Previous](previous.png)](cchartobjecteditcreate.md) 
[![Next](next.png)](cchartobjecteditx_size.md)

TextAlign (Get method)

Gets the value of "TextAlign" property ([text alignment mode)](enum_object_property.md#enum_align_mode).

```
ENUM_ALIGN_MODE  TextAlign() const
```

Return Value

Value of "TextAlign" property of the object assigned to the class instance.

 

TextAlign (Set method)

Sets the value of "TextAlign" property ([text aligment mode)](enum_object_property.md#enum_align_mode).

```
bool  TextAlign(
   ENUM_ALIGN_MODE  align      // property value
   )
```

Parameters

align

[in]  New value of "TextAlign" property.

Return Value

true - success, false - cannot change the property.