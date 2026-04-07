DXShaderCreate



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXShaderCreate

[![Previous](previous.png)](dxinputset.md) 
[![Next](next.png)](dxshadersetlayout.md)

DXShaderCreate

Creates a shader of a specified type.

```
int  DXShaderCreate(
   int                  context,           // graphic context handle   
   ENUM_DX_SHADER_TYPE  shader_type,       // shader type 
   const string         source,            // shader source code
   const string         entry_point,       // entry point
   string&              compile_error      // string for receiving compiler messages
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

shader\_type

[out]  The value from the [ENUM\_DX\_SHADER\_TYPE](dxshadercreate.md#enum_dx_shader_type) enumeration.

source

[in]  Shader source code in [HLSL 5](https://en.wikipedia.org/wiki/High-Level_Shading_Language).

entry\_point

[in]  Entry point function name in a source code.

compile\_error

[in]  String for receiving compilation errors.

Return Value

Handle for shader or INVALID\_HANDLE in case of an error. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

A created handle that is no longer in use should be explicitly released by the [DXRelease()](dxrelease.md) function.

ENUM\_DX\_SHADER\_TYPE

| ID | Value | Description |
| --- | --- | --- |
| DX\_SHADER\_VERTEX | 0 | Vertex shader |
| DX\_SHADER\_GEOMETRY | 1 | Geometry shader |
| DX\_SHADER\_PIXEL | 2 | Pixel shader |