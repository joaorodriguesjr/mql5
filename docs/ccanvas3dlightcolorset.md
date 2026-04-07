LightColorSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / LightColorSet

[![Previous](previous.png)](ccanvas3dlightcolorget.md) 
[![Next](next.png)](ccanvas3dlightdirectionget.md)

LightColorSet

Sets the color and intensity of a directed light source.

```
void  LightColorSet(
   const DXColor  &light_color      // directional lighting color and intensity
   );
```

Parameters

&light\_color

[in]  Directional lighting color and intensity.

Return Value

None.

Note

Intensity is set in the alpha channel of the DXColor structure.