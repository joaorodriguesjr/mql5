OnMouseEvent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / OnMouseEvent

[![Previous](previous.png)](cwndonevent.md) 
[![Next](next.png)](cwndname.md)

OnMouseEvent

Mouse event handler (the [CHARTEVENT\_MOUSE\_MOVE](enum_chartevents.md) chart event).

```
virtual bool  OnMouseEvent(
   const int  x,         // x coordinate
   const int  y,         // y coordinate
   const int  flags      // flags
   )
```

Parameters

x

[in]  X coordinate of the mouse cursor relative to the upper-left corner of the chart.

y

[in]  Y coordinate of the mouse cursor relative to the upper-left corner of the chart.

flags

[in]  Flag of mouse buttons states.

Return Value

true - event has been processed, otherwise - false.