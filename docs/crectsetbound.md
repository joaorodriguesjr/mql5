SetBound



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CRect](crect.md) / SetBound

[![Previous](previous.png)](crectheight.md) 
[![Next](next.png)](crectmove.md)

SetBound

Sets new coordinates of the area using CRect class coordinates.

```
void  SetBound(
   const & CRect  rect      // CRect class
   )
```

Return Value

None.

 

SetBound

Sets new coordinates of the area.

```
void  SetBound(
   const int  l      // left
   const int  t      // top
   const int  r      // right
   const int  b      // bottom
   )
```

Parameters

l

[in]  X coordinate of the upper-left corner.

t

[in]  Y coordinate of the upper-left corner.

r

[in]  X coordinate of the lower-right corner.

b

[in]  Y coordinate of the lower-right corner.

Return Value

None.