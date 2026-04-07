CLKernelFree



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLKernelFree

[![Previous](previous.png)](clkernelcreate.md) 
[![Next](next.png)](clsetkernelarg.md)

CLKernelFree

Removes an OpenCL start function.

```
void  CLKernelFree(
   int  kernel     // Handle to the kernel of an OpenCL program
   );
```

Parameters

kernel\_name

[in]  Handle of the kernel object.

Return Value

None. In the case of an internal error the value of [\_LastError](_lasterror.md) changes. For information about the error, use the [GetLastError()](getlasterror.md) function.