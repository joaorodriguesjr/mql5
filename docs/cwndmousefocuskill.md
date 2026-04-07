MouseFocusKill



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / MouseFocusKill

[![Previous](previous.png)](cwndmouseflags.md) 
[![Next](next.png)](cwndoncreate.md)

MouseFocusKill

Clears the saved state of mouse buttons and deactivates the control.

```
bool  MouseFocusKill(
   const long  id=CONTROLS_INVALID_ID      // id
   )
```

Parameters

id=CONTROLS\_INVALID\_ID

[in]  Identifier of the control, that received mouse focus.

Return Value

The control deactivation result.