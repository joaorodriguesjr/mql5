CLSetKernelArgMemLocal



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLSetKernelArgMemLocal

[![Previous](previous.png)](clsetkernelargmem.md) 
[![Next](next.png)](clbuffercreate.md)

CLSetKernelArgMemLocal

Sets the local buffer as an argument of the kernel function.

```
bool  CLSetKernelArgMemLocal(
   int    kernel,           // handle to a kernel of an OpenCL program
   uint   arg_index,        // number of the OpenCL function argument
   ulong  local_mem_size    // buffer size
   );
```

Parameters

kernel

[in]  Handle to a kernel of the OpenCL program.

arg\_index

[in]  The number of the function argument, numbering starts with zero.

local\_mem\_size

[in]  Buffer size in bytes.

Return Value

Returns true if successful, otherwise returns false. For information about the error, use the [GetLastError()](getlasterror.md) function.