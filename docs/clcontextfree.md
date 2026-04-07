CLContextFree



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLContextFree

[![Previous](previous.png)](clcontextcreate.md) 
[![Next](next.png)](clgetdeviceinfo.md)

CLContextFree

Removes an OpenCL context.

```
void  CLContextFree(
   int  context     // Handle to an OpenCL context
   );
```

Parameters

context

[in]  Handle of the OpenCL context.

Return Value

None. In the case of an internal error the value of [\_LastError](_lasterror.md) changes. For information about the error, use the [GetLastError()](getlasterror.md) function.