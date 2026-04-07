ColorBackground



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / ColorBackground

[![Previous](previous.png)](cwndobjcolor.md) 
[![Next](next.png)](cwndobjcolorborder.md)

ColorBackground (Get method)

Gets the [OBJPROP\_BGCOLOR](enum_object_property.md#enum_object_property_integer) (background color) of the chart object.

```
color  ColorBackground()
```

Return Value

The value of the [OBJPROP\_BGCOLOR](enum_object_property.md#enum_object_property_integer) property.

 

ColorBackground (Set method)

Sets the [OBJPROP\_BGCOLOR](enum_object_property.md#enum_object_property_integer) (background color) property of the chart object.

```
bool  ColorBackground(
   const color  value      // value
   )
```

Parameters

value

[in]  New value of the [OBJPROP\_BGCOLOR](enum_object_property.md#enum_object_property_integer) property.

Return Value

true - successful, otherwise - false.