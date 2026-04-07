DXInputCreate



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXInputCreate

[![Previous](previous.png)](dxtexturecreate.md) 
[![Next](next.png)](dxinputset.md)

DXInputCreate

Creates shader inputs.

```
int  DXInputCreate(
   int   context,        // graphic context handle
   uint  input_size      // size of inputs in bytes 
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

input\_size

[in]  Size of the parameter structure in bytes.

Return Value

The handle for shader inputs or INVALID\_HANDLE in case of an error. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

A created handle that is no longer in use should be explicitly released by the [DXRelease()](dxrelease.md) function.