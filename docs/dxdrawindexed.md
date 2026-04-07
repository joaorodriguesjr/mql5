DXDrawIndexed



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXDrawIndexed

[![Previous](previous.png)](dxdraw.md) 
[![Next](next.png)](dxprimivetopologyset.md)

DXDrawIndexed

Renders graphic primitives described by the index buffer from [DXBufferSet()](dxbufferset.md).

```
bool  DXDrawIndexed(
   int   context,               // graphic context handle 
   uint  start=0,               // first primitive index
   uint  count=WHOLE_ARRAY      // number of primitives
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

start=0

[in]  Index of the first primitive for rendering.

count=WHOLE\_ARRAY

[in]  Number of primitives for rendering.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The type of primitives described by the index buffer is set using [DXPrimiveTopologySet()](dxprimivetopologyset.md).

The vertex buffer in [DXBufferSet()](dxbufferset.md) should be preliminarily set to render primitives.

Also, shaders should be preliminarily set using [DXShaderSet()](dxshaderset.md).