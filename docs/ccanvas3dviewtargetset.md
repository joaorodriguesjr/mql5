ViewTargetSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / ViewTargetSet

[![Previous](previous.png)](ccanvas3dviewrotationset.md) 
[![Next](next.png)](ccanvas3dviewupdirectionset.md)

ViewTargetSet

Sets the coordinates of the point a gaze is directed at.

```
void  ViewTargetSet(
   const DXVector3  &target      // target coordinates
   );
```

Parameters

&target

[in]  Coordinates of the point a gaze is directed at.

Return Value

None.

Note

Used to fix the gaze at one scene point when moving the viewpoint.

Setting a new target coordinate using ViewRotationSet() changes the view matrix obtained in [ViewMatrixGet()](ccanvas3dviewmatrixget.md).

ViewTargetSet() is used together with [ViewUpDirectionSet()](ccanvas3dviewupdirectionset.md) to define the gaze direction.