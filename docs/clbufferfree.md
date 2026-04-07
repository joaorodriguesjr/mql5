CLBufferFree



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLBufferFree

[![Previous](previous.png)](clbuffercreate.md) 
[![Next](next.png)](clbufferwrite.md)

CLBufferFree

Deletes an OpenCL buffer.

```
void  CLBufferFree(
   int   buffer     // Handle to an OpenCL buffer
   );
```

Parameters

buffer

[in]  A handle to an OpenCL buffer.

Return Value

None. In the case of an internal error the value of [\_LastError](_lasterror.md) changes. For information about the error, use the [GetLastError()](getlasterror.md) function.