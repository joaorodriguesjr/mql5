DXDraw



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXDraw

[![Previous](previous.png)](dxshadertexturesset.md) 
[![Next](next.png)](dxdrawindexed.md)

DXDraw

Renders the vertices of the vertex buffer set in [DXBufferSet()](dxbufferset.md).

```
bool  DXDraw(
   int   context,               // graphic context handle 
   uint  start=0,               // first vertex index
   uint  count=WHOLE_ARRAY      // number of vertices
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

start=0

[in]  Index of the first vertex for rendering.

count=WHOLE\_ARRAY

[in]  Number of vertices to render.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

Shaders should be preliminarily set using [DXShaderSet()](dxshaderset.md) for rendering vertices.