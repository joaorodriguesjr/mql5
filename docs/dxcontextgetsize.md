DXContextGetSize



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXContextGetSize

[![Previous](previous.png)](dxcontextsetsize.md) 
[![Next](next.png)](dxcontextclearcolors.md)

DXContextGetSize

Gets a frame size of a graphic context created in [DXContextCreate()](dxcontextcreate.md).

```
bool  DXContextGetSize(
   int    context,      // graphic context handle   
   uint&  width,        // width in pixels 
   uint&  height        // height in pixels 
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

width

[out]  Frame width in pixels.

height

[out]  Frame height in pixels.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.