OnSetFontSize



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnSetFontSize

[![Previous](previous.png)](cwndobjonsetfont.md) 
[![Next](next.png)](cwndobjonsetzorder.md)

OnSetFontSize

The virtual handler of "SetFontSize" (change of the [OBJPROP\_FONTSIZE](enum_object_property.md#enum_object_property_integer) property) event.

```
virtual bool  OnSetFontSize()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.