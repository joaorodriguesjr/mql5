DXShaderTexturesSet



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXShaderTexturesSet

[![Previous](previous.png)](dxshaderinputsset.md) 
[![Next](next.png)](dxdraw.md)

DXShaderTexturesSet

Sets shader textures.

```
bool  DXShaderTexturesSet(
   int          shader,         // shader handle
   const  int&  textures[]      // array of structure handles
   );
```

Parameters

shader

[in]  Handle of a shader created in [DXShaderCreate()](dxshadercreate.md).

textures[]

[in]  Array of texture handles created using [DXTextureCreate()](dxtexturecreate.md).

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

The size of the texture array should be equal to the number of [Texture2D](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl-to-type) objects declared in the shader code.