ControlFind



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / ControlFind

[![Previous](previous.png)](cwndcontrol.md) 
[![Next](next.png)](cwndrect.md)

ControlFind

Gets the control from container by specified ID.

```
virtual CWnd*  ControlFind(
   const long  id      // ID
   )
```

Parameters

id

[in]  Identifier of the control to find.

Return Value

Pointer to the control from the container.

Note

The base class method does not have the container, it provides the access to container for its heirs. If the specified ID matches the container's one, it returns a pointer to itself (this).