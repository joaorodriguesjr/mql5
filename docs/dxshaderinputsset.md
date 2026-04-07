DXShaderInputsSet



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXShaderInputsSet

[![Previous](previous.png)](dxshadersetlayout.md) 
[![Next](next.png)](dxshadertexturesset.md)

DXShaderInputsSet

Sets shader inputs.

```
bool  DXShaderInputsSet(
   int         shader,       // shader handle
   const int&  inputs[]      // array of input handles
   );
```

Parameters

shader

[in]  Handle of a shader created in [DXShaderCreate()](dxshadercreate.md).

inputs[]

[in]  Array of input handles created using [DXInputCreate()](dxinputcreate.md).

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The size of the input parameter should be equal to the number of [cbuffer](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl-constants) objects declared in the shader code.