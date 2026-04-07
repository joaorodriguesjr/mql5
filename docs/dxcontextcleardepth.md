DXContextClearDepth



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXContextClearDepth

[![Previous](previous.png)](dxcontextclearcolors.md) 
[![Next](next.png)](dxcontextgetcolors.md)

DXContextClearDepth

Clears the depth buffer.

```
bool  DXContextClearDepth(
   int  context      // graphic context handle 
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The DXContextClearDepth() function can be used for clearing the depth buffer before rendering the next frame.