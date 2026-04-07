DXBufferSet



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXBufferSet

[![Previous](previous.png)](dxprimivetopologyset.md) 
[![Next](next.png)](dxshaderset.md)

DXBufferSet

Sets a buffer for the current rendering.

```
bool  DXBufferSet(
   int   context,               // graphic context handle
   int   buffer,                // vertex or index buffer handle
   uint  start=0,               // initial index
   uint  count=WHOLE_ARRAY      // number of elements 
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

buffer

[in]  Handle of the vertex or index buffer created in [DXBufferCreate()](dxbuffercreate.md).

start=0

[in]  Index of the buffer first element. The data from the beginning of the buffer is used by default.

count=WHOLE\_ARRAY

[in]  Number of values to be used. The default is all buffer values.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The DXBufferSet() function should be called to set vertex and index buffers for rendering using [DXDraw()](dxdraw.md).