ViewUpDirectionSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / ViewUpDirectionSet

[![Previous](previous.png)](ccanvas3dviewtargetset.md) 
[![Next](next.png)](cchart.md)

ViewUpDirectionSet

Sets the direction of the upper frame border in 3D space.

```
void  ViewUpDirectionSet(
   const DXVector3  &up_direction      // top direction
   );
```

Parameters

&up\_direction

[in]  Direction of the upper part of the frame in 3D space.

Return Value

None.

Note

Setting a new direction using ViewUpDirectionSet() changes the view matrix obtained in [ViewMatrixGet()](ccanvas3dviewmatrixget.md).

ViewUpDirectionSet() is used together with [ViewTargetSet()](ccanvas3dviewtargetset.md) to define the gaze direction.