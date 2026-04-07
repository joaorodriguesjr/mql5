ObjectAdd



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / ObjectAdd

[![Previous](previous.png)](ccanvas3dlightdirectionset.md) 
[![Next](next.png)](ccanvas3dprojectionmatrixget.md)

ObjectAdd

Adds an object to a 3D scene for subsequent rendering.

```
bool  ObjectAdd(
   CDXObject  *object      // pointer to the object
   );
```

Parameters

*object

[in]  Pointer to an instance of the class derived from the CDXObject abstract class.

Return Value

true if successful, false - if failed to add a 3D graphic object.