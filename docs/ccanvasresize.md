Resize



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / Resize

[![Previous](previous.png)](ccanvasrectangle.md) 
[![Next](next.png)](ccanvasresourcename.md)

Resize

Resizes a graphical resource.

```
bool  Resize(
   const int  width,      // width
   const int  height      // height
   );
```

Parameters

width

[in]  New width of a graphical resource.

height

[in]  New height of a graphical resource.

Return Value

true - successful, otherwise - false

Note

When resizing, the previous image is not saved.