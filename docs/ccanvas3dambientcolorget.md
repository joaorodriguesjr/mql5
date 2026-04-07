AmbientColorGet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / AmbientColorGet

[![Previous](previous.png)](ccanvas3d.md) 
[![Next](next.png)](ccanvas3dambientcolorset.md)

AmbientColorGet

Gets the color and intensity of the ambient all-round lighting.

```
void  AmbientColorGet(
   DXColor  &ambient_color      // all-round lighting color and intensity
   );
```

Parameters

&ambient\_color

[out]  All-round lighting color.

Return Value

No

Note

Intensity is stored in the alpha channel of the DXColor structure.