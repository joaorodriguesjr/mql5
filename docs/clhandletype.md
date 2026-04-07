CLHandleType



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLHandleType

[![Previous](previous.png)](opencl.md) 
[![Next](next.png)](clgetinfointeger.md)

CLHandleType

Returns the type of an OpenCL handle as a value of the ENUM\_OPENCL\_HANDLE\_TYPE enumeration.

```
ENUM_OPENCL_HANDLE_TYPE  CLHandleType(
   int  handle     // Handle of an OpenCL object
   );
```

Parameters

handle

[in]  A handle to an OpenCL object: a context, a kernel or an OpenCL program.

Return Value

The type of the OpenCL handle as a value of the [ENUM\_OPENCL\_HANDLE\_TYPE](clhandletype.md#enum_opencl_handle_type) enumeration.

ENUM\_OPENCL\_HANDLE\_TYPE

| Identifier | Description |
| --- | --- |
| OPENCL\_INVALID | Incorrect handle |
| OPENCL\_CONTEXT | A handle of the OpenCL context |
| OPENCL\_PROGRAM | A handle of the OpenCL program |
| OPENCL\_KERNEL | A handle of the OpenCL kernel |
| OPENCL\_BUFFER | A handle of the OpenCL buffer |