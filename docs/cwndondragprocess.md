OnDragProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / OnDragProcess

[![Previous](previous.png)](cwndondragstart.md) 
[![Next](next.png)](cwndondragend.md)

OnDragProcess

The virtual handler of the "DragProcess" (dragging) event.

```
virtual bool  OnDragProcess(
   const int  x,     // x coordinate
   const int  y      // y coordinate
   )
```

Parameters

x

[in] Current X coordinate of mouse cursor.

y

[in]  Current Y coordinate of mouse cursor.

Return Value

true - event processed, otherwise - false.

Note

The "DragProcess" event occurs when the control is dragged.