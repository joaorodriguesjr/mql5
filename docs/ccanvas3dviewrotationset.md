ViewRotationSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / ViewRotationSet

[![Previous](previous.png)](ccanvas3dviewpositionset.md) 
[![Next](next.png)](ccanvas3dviewtargetset.md)

ViewRotationSet

Sets the direction of a gaze at a 3D scene.

```
void  ViewRotationSet(
   const DXVector3  &rotation      // vector of turning angles 
   );
```

Parameters

&rotation

[in]  Vector setting Euler angles to calculate the direction of a gaze at a 3D scene.

Return Value

None.

Note

Setting the gaze direction using ViewRotationSet() changes the view matrix obtained in [ViewMatrixGet()](ccanvas3dviewmatrixget.md).