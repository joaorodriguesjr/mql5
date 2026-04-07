TextAlign



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CEdit](cedit.md) / TextAlign

[![Previous](previous.png)](ceditreadonly.md) 
[![Next](next.png)](ceditonobjectendedit.md)

TextAlign (Get method)

Gets the value of "TextAlign" property ([text alignment mode](enum_object_property.md#enum_align_mode)) of the control.

```
ENUM_ALIGN_MODE  TextAlign() const
```

Return Value

Value of "TextAlign" property of the control.

 

TextAlign (Set method)

Sets new value of "TextAlign" property ([text aligment mode](enum_object_property.md#enum_align_mode)) of the control.

```
bool  TextAlign(
   ENUM_ALIGN_MODE  align      // property value
   )
```

Parameters

align

[in]  New value of "TextAlign" property.

Return Value

true - successful, false - cannot change the property.