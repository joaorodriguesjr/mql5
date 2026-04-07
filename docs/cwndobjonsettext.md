OnSetText



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnSetText

[![Previous](previous.png)](cwndobjonobjectdrag.md) 
[![Next](next.png)](cwndobjonsetcolor.md)

OnSetText

The virtual handler of control "SetText" (change of the [OBJPROP\_TEXT](enum_object_property.md#enum_object_property_double) property) event.

```
virtual bool  OnSetText()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.