DXContextGetDepth



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXContextGetDepth

[![Previous](previous.png)](dxcontextgetcolors.md) 
[![Next](next.png)](dxbuffercreate.md)

DXContextGetDepth

Gets the depth buffer of a rendered frame.

```
bool  DXContextGetDepth(
   int     context,      // graphic context handle   
   float&  image[]       // depth value array 
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

image

[out]  Array of the rendered frame depth buffer values.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The returned buffer contains the depth of each pixel of a rendered frame that can be obtained in [DXContextGetColors()](dxcontextgetcolors.md) in relative units (from 0.0 to 1.0).