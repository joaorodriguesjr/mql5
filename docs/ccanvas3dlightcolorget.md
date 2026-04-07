LightColorGet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / LightColorGet

[![Previous](previous.png)](ccanvas3dinputscene.md) 
[![Next](next.png)](ccanvas3dlightcolorset.md)

LightColorGet

Gets the color and intensity of a directed light source.

```
void  LightColorGet(
   DXColor  &light_color      // directional lighting color and intensity
   );
```

Parameters

&light\_color

[out]  Directional lighting color and intensity.

Return Value

None.

Note

Intensity is stored in the alpha channel of the DXColor structure.