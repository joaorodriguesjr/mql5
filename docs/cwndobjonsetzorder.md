OnSetZOrder



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnSetZOrder

[![Previous](previous.png)](cwndobjonsetfontsize.md) 
[![Next](next.png)](cwndobjondestroy.md)

OnSetZOrder

The virtual handler of "SetZOrder" (change of the [OBJPROP\_ZORDER](enum_object_property.md#enum_object_property_integer) property) event.

```
virtual bool  OnSetZOrder()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.