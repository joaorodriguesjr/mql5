OnThumbDragProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CScroll](cscroll.md) / OnThumbDragProcess

[![Previous](previous.png)](cscrollonthumbdragstart.md) 
[![Next](next.png)](cscrollonthumbdragend.md)

OnThumbDragProcess

The virtual handler of the control "ThumbDragProcess" event.

```
virtual bool  OnThumbDragProcess(
   const int  x,     // x coordinate
   const int  y      // y coordinate
   )
```

Parameters

x

[in]  Current X coordinate of mouse cursor.

y

[in]  Current Y coordinate of mouse cursor.

Return Value

true - event processed, otherwise - false.

Note

The "ThumbDragProcess" occurs when the scroll bar control (thumb button) is moved.