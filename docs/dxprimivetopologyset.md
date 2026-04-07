DXPrimiveTopologySet



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXPrimiveTopologySet

[![Previous](previous.png)](dxdrawindexed.md) 
[![Next](next.png)](dxbufferset.md)

DXPrimiveTopologySet

Sets the type of primitives for rendering using [DXDrawIndexed()](dxdrawindexed.md).

```
bool  DXPrimiveTopologySet(
   int                         context,                // graphic context handle
   ENUM_DX_PRIMITIVE_TOPOLOGY  primitive_topology      // primitive type
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

primitive\_topology

[in]  The value from the [ENUM\_DX\_PRIMITIVE\_TOPOLOGY](dxprimivetopologyset.md#enum_dx_primitive_topology) enumeration.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

 

ENUM\_DX\_PRIMITIVE\_TOPOLOGY

| ID | Value | Match in [D3D11\_PRIMITIVE\_TOPOLOGY](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/ff476189(v%3Dvs.85)) |
| --- | --- | --- |
| DX\_PRIMITIVE\_TOPOLOGY\_POINTLIST | 1 | D3D11\_PRIMITIVE\_TOPOLOGY\_POINTLIST |
| DX\_PRIMITIVE\_TOPOLOGY\_LINELIST | 2 | D3D11\_PRIMITIVE\_TOPOLOGY\_LINELIST |
| DX\_PRIMITIVE\_TOPOLOGY\_LINESTRIP | 3 | D3D11\_PRIMITIVE\_TOPOLOGY\_LINESTRIP |
| DX\_PRIMITIVE\_TOPOLOGY\_TRIANGLELIST | 4 | D3D11\_PRIMITIVE\_TOPOLOGY\_TRIANGLELIST |
| DX\_PRIMITIVE\_TOPOLOGY\_TRIANGLESTRIP | 5 | D3D11\_PRIMITIVE\_TOPOLOGY\_TRIANGLESTRIP |
| DX\_PRIMITIVE\_TOPOLOGY\_LINELIST\_ADJ | 6 | D3D11\_PRIMITIVE\_TOPOLOGY\_LINELIST\_ADJ |
| DX\_PRIMITIVE\_TOPOLOGY\_LINESTRIP\_ADJ | 7 | D3D11\_PRIMITIVE\_TOPOLOGY\_LINESTRIP\_ADJ |
| DX\_PRIMITIVE\_TOPOLOGY\_TRIANGLELIST\_ADJ | 8 | D3D11\_PRIMITIVE\_TOPOLOGY\_TRIANGLELIST\_ADJ |
| DX\_PRIMITIVE\_TOPOLOGY\_TRIANGLESTRIP\_ADJ | 9 | D3D11\_PRIMITIVE\_TOPOLOGY\_TRIANGLESTRIP\_ADJ |