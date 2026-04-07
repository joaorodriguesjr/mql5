Render



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / Render

[![Previous](previous.png)](ccanvas3dprojectionmatrixset.md) 
[![Next](next.png)](ccanvas3drenderbegin.md)

Render

Renders all scene objects in the frame inner buffer for subsequent display.

```
bool  Render(
   uint  flags,                  // combination of flags
   uint  background_color=0      // background color
   );
```

Parameters

flags

[in]  Combination of flags that sets the rendering mode. Possible values:  
DX\_CLEAR\_COLOR clear the image buffer using background\_color.  
DX\_CLEAR\_DEPTH clear the depth buffer.

background\_color=0

[in]  3D scene background color.

Return Value

true if successful, false if failed to render.

Note

Calling Render() does not update a scene on a chart. Instead, it only updates the inner buffer of the image. The Update() method should be explicitly called to render the updated frame.

Render() features the [RenderBegin](ccanvas3drenderbegin.md) and [RenderEnd()](ccanvas3drenderend.md) calls.