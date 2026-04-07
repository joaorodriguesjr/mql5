DXRelease



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXRelease

[![Previous](previous.png)](dxhandletype.md) 
[![Next](next.png)](python_metatrader5.md)

DXRelease

Releases a handle.

```
bool  DXRelease(
   int  handle      // handle 
   );
```

Parameters

context

[in]  Released handle.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

Note

All created handles that are no longer in use should be explicitly released by the DXRelease() function.