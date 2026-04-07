ControlFind



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndContainer](cwndcontainer.md) / ControlFind

[![Previous](previous.png)](cwndcontainercontrol.md) 
[![Next](next.png)](cwndcontaineradd.md)

ControlFind

Gets control from the container by identifier.

```
virtual CWnd*  ControlFind(
   const long  id      // id
   )
```

Parameters

id

[in]  Control ID.

Return Value

Pointer to the control, otherwise NULL if the control is not found.