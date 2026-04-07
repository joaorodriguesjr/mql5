DXContextCreate



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXContextCreate

[![Previous](previous.png)](directx.md) 
[![Next](next.png)](dxcontextsetsize.md)

DXContextCreate

Creates a graphic context for rendering frames of a specified size.

```
int  DXContextCreate(
   uint  width,      // width in pixels
   uint  height      // height in pixels
   );
```

Parameters

width

[in]  Frame width in pixels.

height

[in]  Frame height in pixels.

Return Value

A handle for a created context or INVALID\_HANDLE in case of an error. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

All graphical objects created using the [DXBufferCreate](dxbuffercreate.md), [DXInputCreate](dxinputcreate.md), [DXShaderCreate](dxshadercreate.md) and [DXTextureCreate](dxtexturecreate.md) functions can be used only in a graphic context they were created in.

A frame size can subsequently be changed to [DXContextSetSize()](dxcontextsetsize.md).

A created handle that is no longer in use should be explicitly released by the [DXRelease()](dxrelease.md) function.