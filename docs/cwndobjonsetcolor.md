OnSetColor



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnSetColor

[![Previous](previous.png)](cwndobjonsettext.md) 
[![Next](next.png)](cwndobjonsetcolorbackground.md)

OnSetColor

The virtual handler of control "SetColor" (change of the [OBJPROP\_COLOR](enum_object_property.md#enum_object_property_integer) property) event.

```
virtual bool  OnSetColor()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.