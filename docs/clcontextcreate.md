CLContextCreate



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLContextCreate

[![Previous](previous.png)](clgetinfostring.md) 
[![Next](next.png)](clcontextfree.md)

CLContextCreate

Creates an OpenCL context and returns its handle.

```
int  CLContextCreate(
   int  device=CL_USE_ANY     // Serial number of the OpenCL device or macro
   );
```

Parameter

device

[in]  The ordinal number of the OpenCL-device in the system. Instead of a specific number, you can specify one of the following values:

* CL\_USE\_ANY any available device with OpenCL support is allowed;
* CL\_USE\_CPU\_ONLY only OpenCL emulation on CPU is allowed;
* CL\_USE\_GPU\_ONLY OpenCL emulation is prohibited and only specialized devices with OpenCL support (video cards) can be used;

* CL\_USE\_GPU\_DOUBLE\_ONLY  only the GPUs that support type [double](double.md) are allowed.

Return Value

A handle to the OpenCL context if successful, otherwise -1. For information about the error, use the [GetLastError()](getlasterror.md) function.