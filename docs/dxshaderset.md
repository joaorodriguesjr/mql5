DXShaderSet



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXShaderSet

[![Previous](previous.png)](dxbufferset.md) 
[![Next](next.png)](dxhandletype.md)

DXShaderSet

Sets a shader for rendering.

```
bool  DXShaderSet(
   int  context,      // graphic context handle
   int  shader        // shader handle
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

shader

[in]  Handle of a shader created in [DXShaderCreate()](dxshadercreate.md).

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

Several types of shaders can simultaneously be used for rendering (vertex, geometry and pixel ones).