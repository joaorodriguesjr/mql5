OnSetFont



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnSetFont

[![Previous](previous.png)](cwndobjonsetcolorbackground.md) 
[![Next](next.png)](cwndobjonsetfontsize.md)

OnSetFont

The virtual handler of "SetFont" (change of the [OBJPROP\_FONT](enum_object_property.md#enum_object_property_string) property) event.

```
virtual bool  OnSetFont()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.