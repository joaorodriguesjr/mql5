OnSetColorBackground



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnSetColorBackground

[![Previous](previous.png)](cwndobjonsetcolor.md) 
[![Next](next.png)](cwndobjonsetfont.md)

OnSetColorBackground

The virtual handler of control "SetColorBackground" (change of the [OBJPROP\_BGCOLOR](enum_object_property.md#enum_object_property_integer) property) event.

```
virtual bool  OnSetColorBackground()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.