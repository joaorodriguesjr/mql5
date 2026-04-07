PixelGet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / PixelGet

[![Previous](previous.png)](ccanvasloadfromfile.md) 
[![Next](next.png)](ccanvaspixelset.md)

PixelGet

Receives color of the point with the specified coordinates.

```
uint  PixelGet(
   const int  x,     // X coordinate
   const int  y      // Y coordinate
   );
```

Parameters

x

[in]  Point's X coordinate.

y

[in]  Point's Y coordinate.

Return Value

Point color in ARGB format.