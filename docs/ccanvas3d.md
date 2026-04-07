CCanvas3D



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md) / CCanvas3D

[![Previous](previous.png)](3dgraphics.md) 
[![Next](next.png)](ccanvas3dambientcolorget.md)

CCanvas3D

CCanvas3D is a class for simplified creation and visualization of 3D objects on a chart.

Description

CCanvas3D greatly simplifies creation and visualization of large amounts of data in the form of animated 3D graphics. The class contains the methods for managing camera and lighting, as well as features the resource manager for creating graphic resources: textures, shaders, vertex buffers, indexes, and shader parameters.

Besides, the library contains the classes of the scene base objects, such as a box, a three-dimensional surface on user data, or an arbitrary grid.

A video card should support DX 11 and Shader Model 5.0 for the functions to work.

Declaration

```
   class CCanvas
```

Title

```
   #include <Canvas\Canvas.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CCanvas](ccanvas.md)        CCanvas3D |

Class methods by groups

| Creating/deleting | Description |
| --- | --- |
| [Create](ccanvas3dcreate.md) | Creates a graphic resource for rendering a 3D scene without binding to a chart object. |
| [Attach](ccanvas3dattach.md) | Gets a graphical resource from the OBJ\_BITMAP\_LABEL object and attaches it to an instance of the CCanvas class. |
| [ObjectAdd](ccanvas3dobjectadd.md) | Adds an object to a 3D scene for subsequent rendering. |
| [Destroy](ccanvas3ddestroy.md) | Destroys a graphic resource and releases a graphic 3D context. |
| Light |  |
| [AmbientColorSet](ccanvas3dambientcolorset.md) | Sets the color and intensity of the ambient all-round lighting. |
| [AmbientColorGet](ccanvas3dambientcolorget.md) | Gets the color and intensity of the ambient all-round lighting. |
| [LightDirectionSet](ccanvas3dlightdirectionset.md) | Sets the direction of a directed light source. |
| [LightDirectionGet](ccanvas3dlightdirectionget.md) | Gets the direction of a directed light source. |
| [LightColorSet](ccanvas3dlightcolorset.md) | Sets the color and intensity of a directed light source. |
| [LightColorGet](ccanvas3dlightcolorget.md) | Gets the color and intensity of a directed light source. |
| Camera |  |
| [ProjectionMatrixSet](ccanvas3dprojectionmatrixset.md) | Calculates and sets a 3D coordinate projection matrix to a 2D frame. |
| [ProjectionMatrixGet](ccanvas3dprojectionmatrixget.md) | Gets a 3D scene projection matrix to a 2D frame. |
| [ViewMatrixSet](ccanvas3dviewmatrixset.md) | Sets a 3D scene view matrix. |
| [ViewMatrixGet](ccanvas3dviewmatrixget.md) | Returns a 3D scene view matrix. |
| [ViewPositionSet](ccanvas3dviewpositionset.md) | Sets a viewpoint on a 3D scene. |
| [ViewRotationSet](ccanvas3dviewrotationset.md) | Sets the direction of a gaze at a 3D scene. |
| [ViewTargetSet](ccanvas3dviewtargetset.md) | Sets the coordinates of the point a gaze is directed at. |
| [ViewUpDirectionSet](ccanvas3dviewupdirectionset.md) | Sets the direction of the upper frame border in 3D space. |
| Rendering |  |
| [Render](ccanvas3drender.md) | Renders all scene objects in the frame inner buffer for subsequent display. |
| [RenderBegin](ccanvas3drenderbegin.md) | Prepares a graphic context for rendering a new frame. |
| [RenderEnd](ccanvas3drenderend.md) | Copies a rendered frame to the inner buffer and updates a chart image if necessary. |
| Getting resources |  |
| [DXContext](ccanvas3ddxcontext.md) | Gets the graphic context handle. |
| [DXDispatcher](ccanvas3ddxdispatcher.md) | Gets the resource dispatcher handle. |
| [InputScene](ccanvas3dinputscene.md) | Gets the pointer to the buffer of scene parameters. |