ViewPositionSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / ViewPositionSet

[![Previous](previous.png)](ccanvas3dviewmatrixset.md) 
[![Next](next.png)](ccanvas3dviewrotationset.md)

ViewPositionSet

Sets a viewpoint on a 3D scene.

```
void  ViewPositionSet(
   const DXVector3  &position      // viewpoint position
   );
```

Parameters

&position

[in]  Setting a viewpoint position on a 3D scene.

Return Value

None.

Note

Setting a viewpoint position using ViewPositionSet() changes the view matrix obtained in [ViewMatrixGet()](ccanvas3dviewmatrixget.md).