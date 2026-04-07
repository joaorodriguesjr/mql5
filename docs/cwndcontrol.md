Control



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / Control

[![Previous](previous.png)](cwndcontrolstotal.md) 
[![Next](next.png)](cwndcontrolfind.md)

Control

Gets the control from the container by index.

```
CWnd*  Control(
   const int  ind      // index
   )  const
```

Parameters

ind

[in]  Control index.

Return Value

A pointer to the control.

Note

The base class method does not have the container, it provides the access to container for its heirs and always returns NULL.