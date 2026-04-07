PolylineAA



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / PolylineAA

[![Previous](previous.png)](ccanvaspolylinewu.md) 
[![Next](next.png)](ccanvasrectangle.md)

PolylineAA

Draws a polyline using antialiasing algorithm.

```
void  PolylineAA(
   int&        x[],                // array of X coordinates
   int&        y[],                // array of Y coordinates
   const uint  clr,                // color
   const uint  style=UINT_MAX      // line style
   );
```

Parameters

x[]

[in]  Array of X coordinates of a polyline.

y[]

[in]  Array of Y coordinates of a polyline.

clr

[in]  Color in ARGB format.

style=UINT\_MAX

[in]  Line style is one of [ENUM\_LINE\_STYLE](drawstyles.md#enum_line_style) enumeration's values or a custom value.