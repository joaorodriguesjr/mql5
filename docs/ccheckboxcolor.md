Color



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CCheckBox](ccheckbox.md) / Color

[![Previous](previous.png)](ccheckboxtext.md) 
[![Next](next.png)](ccheckboxchecked.md)

Color (Get method)

Gets color of the label associated with the control.

```
color  Color()  const
```

Return Value

Label color.

 

Color (Set method)

Sets color of the label associated with the control.

```
bool  Color(
   const color  value      // color
   )
```

Parameters

value

[in]  New label color.

Return Value

true - successful, otherwise - false.

Note

Label color is specified by setting [OBJPROP\_COLOR](enum_object_property.md#enum_object_property_integer) (color) of a chart object.