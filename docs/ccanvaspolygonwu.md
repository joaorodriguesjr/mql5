PolygonWu



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / PolygonWu

[![Previous](previous.png)](ccanvaspolygonaa.md) 
[![Next](next.png)](ccanvaspolygonthick.md)

PolygonWu

Draws a polygon using Wu's anti-aliasing algorithm.

```
void  PolygonWu(
   int&        x[],                // array of X coordinates
   int&        y[],                // array of Y coordinates
   const uint  clr,                // color
   const uint  style=UINT_MAX      // line style
   );
```

Parameters

x[]

[in]  Array of X coordinates of a polygon points.

y[]

[in]  Array of Y coordinates of a polygon points.

clr

[in]  Color in ARGB format.

style=UINT\_MAX

[in]  Line style is one of [ENUM\_LINE\_STYLE](drawstyles.md#enum_line_style) enumeration's values or a custom value.