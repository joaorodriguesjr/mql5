DXInputSet



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXInputSet

[![Previous](previous.png)](dxinputcreate.md) 
[![Next](next.png)](dxshadercreate.md)

DXInputSet

Sets shader inputs.

```
bool  DXInputSet(
   int          input,      // graphic context handle
   const void&  data        // data for setting  
   );
```

Parameters

input

[in]  Handle of inputs for a shader obtained in [DXInputCreate()](dxinputcreate.md).

data

[in]  Data for setting shader inputs.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.