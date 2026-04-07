MouseFocusKill



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndContainer](cwndcontainer.md) / MouseFocusKill

[![Previous](previous.png)](cwndcontainerhide.md) 
[![Next](next.png)](cwndcontainersave.md)

MouseFocusKill

Clears the saved state of mouse buttons and deactivates all controls in the container.

```
bool  MouseFocusKill(
   const long  id=CONTROLS_INVALID_ID      // id
   )
```

Parameters

id=CONTROLS\_INVALID\_ID

[in]  Identifier of the control, that received mouse focus.

Return Value

The controls deactivation result.