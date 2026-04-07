ColorBorder



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / ColorBorder

[![Previous](previous.png)](cwndobjcolorbackground.md) 
[![Next](next.png)](cwndobjfont.md)

ColorBorder (Get method)

Gets the [OBJPROP\_BORDER\_COLOR](enum_object_property.md#enum_object_property_integer) (border color) property of the chart object.

```
color  ColorBorder()
```

Return Value

The value of the [OBJPROP\_BORDER\_COLOR](enum_object_property.md#enum_object_property_integer) property.

 

ColorBorder (Set method)

Sets the [OBJPROP\_BORDER\_COLOR](enum_object_property.md#enum_object_property_integer) (border color) property of the chart object.

```
bool  ColorBorder(
   const color  value      // value
   )
```

Parameters

value

[in]  New value of the [OBJPROP\_BORDER\_COLOR](enum_object_property.md#enum_object_property_integer) property.

Return Value

true - successful, otherwise - false.