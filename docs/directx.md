Working with DirectX



[MQL5 Reference](index.md) / Working with DirectX

[![Previous](previous.png)](databasecolumnblob.md) 
[![Next](next.png)](dxcontextcreate.md)

Working with DirectX

DirectX 11 functions and shaders are designed for 3D visualization directly on a price chart.

Creating 3D graphics requires a graphic context ([DXContextCreate](dxcontextcreate.md)) with the necessary image size. Besides, it is necessary to prepare vertex and index buffers ([DXBufferCreate](dxbuffercreate.md)), as well as create vertex and pixel shaders ([DXShaderCreate](dxshadercreate.md)). This is enough to display graphics in color.

The next level of graphics requires the inputs ([DXInputSet](dxinputset.md)) for passing additional rendering parameters to shaders. This allows setting the camera and 3D object positions, describe light sources and implement mouse and keyboard control.

Thus, the built-in MQL5 functions enable you to create animated 3D charts directly in MetaTrader 5 with no need for third-party tools. A video card should support DX 11 and Shader Model 5.0 for the functions to work.

To start working with the library, simply read the article [How to create 3D graphics using DirectX in MetaTrader 5](https://www.mql5.com/en/articles/7708).

| Function | Action |
| --- | --- |
| [DXContextCreate](dxcontextcreate.md) | Creates a graphic context for rendering frames of a specified size |
| [DXContextSetSize](dxcontextsetsize.md) | Changes a frame size of a graphic context created in DXContextCreate() |
| [DXContextSetSize](dxcontextsetsize.md) | Gets a frame size of a graphic context created in DXContextCreate() |
| [DXContextClearColors](dxcontextclearcolors.md) | Sets a specified color to all pixels for the rendering buffer |
| [DXContextClearDepth](dxcontextcleardepth.md) | Clears the depth buffer |
| [DXContextGetColors](dxcontextgetcolors.md) | Gets an image of a specified size and offset from a graphic context |
| [DXContextGetDepth](dxcontextgetdepth.md) | Gets the depth buffer of a rendered frame |
| [DXBufferCreate](dxbuffercreate.md) | Creates a buffer of a specified type based on a data array |
| [DXTextureCreate](dxtexturecreate.md) | Creates a 2D texture out of a rectangle of a specified size cut from a passed image |
| [DXInputCreate](dxinputcreate.md) | Creates shader inputs |
| [DXInputSet](dxinputset.md) | Sets shader inputs |
| [DXShaderCreate](dxshadercreate.md) | Creates a shader of a specified type |
| [DXShaderSetLayout](dxshadersetlayout.md) | Sets vertex layout for the vertex shader |
| [DXShaderInputsSet](dxshaderinputsset.md) | Sets shader inputs |
| [DXShaderTexturesSet](dxshadertexturesset.md) | Sets shader textures |
| [DXDraw](dxdraw.md) | Renders the vertices of the vertex buffer set in DXBufferSet() |
| [DXDrawIndexed](dxdrawindexed.md) | Renders graphic primitives described by the index buffer from DXBufferSet() |
| [DXPrimiveTopologySet](dxprimivetopologyset.md) | Sets the type of primitives for rendering using DXDrawIndexed() |
| [DXBufferSet](dxbufferset.md) | Sets a buffer for the current rendering |
| [DXShaderSet](dxshaderset.md) | Sets a shader for rendering |
| [DXHandleType](dxhandletype.md) | Returns a handle type |
| [DXRelease](dxrelease.md) | Releases a handle |