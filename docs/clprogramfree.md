CLProgramFree



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLProgramFree

[![Previous](previous.png)](clprogramcreate.md) 
[![Next](next.png)](clkernelcreate.md)

CLProgramFree

Removes an OpenCL program.

```
void  CLProgramFree(
   int  program     // Handle to an OpenCL object
   );
```

Parameters

program

[in]  Handle of the OpenCL object.

Return Value

None. In the case of an internal error the value of [\_LastError](_lasterror.md) changes. For information about the error, use the [GetLastError()](getlasterror.md) function.