Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CComboBox](ccombobox.md) / Create

[![Previous](previous.png)](ccombobox.md) 
[![Next](next.png)](ccomboboxonevent.md)

Create

Creates CComboBox control.

```
virtual bool  Create(
   const long    chart,      // chart ID
   const string  name,       // name
   const int     subwin,     // chart subwindow
   const int     x1,         // coordinate
   const int     y1,         // coordinate
   const int     x2,         // coordinate
   const int     y2          // coordinate
   )
```

Parameters

chart

[in]  ID of the chat, at which the control is created.

name

[in]  Unique name of the control.

subwin

[in]  Subwindow of the chart, at which the control is created.

x1

[in]  X coordinate of the upper left corner.

y1

[in]  Y coordinate of the upper left corner.

x2

[in]  X coordinate of the lower right corner.

y2

[in]  Y coordinate of the lower right corner.

Return Value

true - successful, otherwise - false.