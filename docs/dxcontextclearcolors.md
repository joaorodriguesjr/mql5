DXContextClearColors



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXContextClearColors

[![Previous](previous.png)](dxcontextgetsize.md) 
[![Next](next.png)](dxcontextcleardepth.md)

DXContextClearColors

Sets a specified color to all pixels for the rendering buffer.

```
bool  DXContextClearColors(
   int              context,      // graphic context handle
   const DXVector&  color         // color
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

color

[in]  Rendering color.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The DXContextClearColors() function can be used for clearing the color buffer before rendering the next frame.