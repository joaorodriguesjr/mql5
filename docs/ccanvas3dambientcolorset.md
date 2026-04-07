AmbientColorSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / AmbientColorSet

[![Previous](previous.png)](ccanvas3dambientcolorget.md) 
[![Next](next.png)](ccanvas3dattach.md)

AmbientColorSet

Sets the color and intensity of the ambient all-round lighting.

```
void  AmbientColorSet(
   const DXColor  &ambient_color      // all-round lighting color and intensity
   );
```

Parameters

&ambient\_color

[in]  All-round lighting color.

Return Value

No

Note

Intensity is set in the alpha channel of the DXColor structure.