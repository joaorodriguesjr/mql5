Text



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CCheckBox](ccheckbox.md) / Text

[![Previous](previous.png)](ccheckboxonevent.md) 
[![Next](next.png)](ccheckboxcolor.md)

Text (Get method)

Gets text of the label associated with the control.

```
string  Text()
```

Return Value

Text of the label.

 

Text (Set method)

Sets text of the label associated with the control.

```
bool  Text(
   const string  value      // text
   )
```

Parameters

value

[in]  New text of the label.

Return Value

true - successful, otherwise - false.

Note

Label text is specified by setting [OBJPROP\_TEXT](enum_object_property.md#enum_object_property_string) (text) of a chart object.