CRect



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CRect

[![Previous](previous.png)](controls.md) 
[![Next](next.png)](crectleft.md)

CRect

CRect is a class of the rectangular area of the chart.

Description

CRect is a class of the area, it is defined by both coordinates of the upper-left and lower-right corners of a rectangle in Cartesian coordinates.

Declaration

```
   class CRect
```

Title

```
   #include <Controls\Rect.mqh>
```

Class Methods by Groups

| Properties |  |
| --- | --- |
| [Left](crectleft.md) | Gets/sets the X coordinate of the upper-left corner |
| [Top](crecttop.md) | Gets/sets the Y coordinate of the upper-left corner |
| [Right](crectright.md) | Gets/sets the X coordinate of the lower-right corner |
| [Bottom](crectbottom.md) | Gets/sets the Y coordinate of the lower-right corner |
| [Width](crectwidth.md) | Gets/sets the width |
| [Height](crectheight.md) | Gets/sets the height |
| [SetBound](crectsetbound.md) | Sets new coordinates of the area |
| [Move](crectmove.md) | Performs the absolute displacement of the area coordinates |
| [Shift](crectshift.md) | Performs the relative displacement (shift) of the area coordinates |
| [Contains](crectcontains.md) | Checks if the point is inside the area |
| Additional methods |  |
| [Format](crectformat.md) | Gets the area coordinates as a string |