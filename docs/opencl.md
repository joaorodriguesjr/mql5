Working with OpenCL



[MQL5 Reference](index.md) / Working with OpenCL

[![Previous](previous.png)](eventchartcustom.md) 
[![Next](next.png)](clhandletype.md)

Working with OpenCL

[OpenCL](https://www.khronos.org/opencl/ "The official website of the OpenCL standard") programs are used for performing computations on video cards that support OpenCL 1.1 or higher. Modern video cards contain hundreds of small specialized processors that can simultaneously perform simple mathematical operations with incoming data streams. The OpenCL language organizes parallel computing and provides greater speed for a certain class of tasks.

In some graphic cards working with the [double](double.md) type numbers is disabled by default. This can lead to compilation error 5105. To enable support for the double type numbers, please add the following directive to your OpenCL program: [#pragma OPENCL EXTENSION cl\_khr\_fp64 : enable](https://www.khronos.org/registry/OpenCL/sdk/1.0/docs/man/xhtml/cl_khr_fp64.md). However if a graphic card doesn't support double, enabling this directive won't be of help.

It is recommended to write the source code for OpenCL in separate CL files, which can later be included in the MQL5 program using the [resource variables](resources.md#resourcevariables).

Handling errors in OpenCL programs

To get information about the last error in an OpenCL program, use the [CLGetInfoInteger](clgetinfointeger.md) and [CLGetInfoString](clgetinfostring.md)functions that allow getting the error code and text description.

OpenCL last error code: To get the latest OpenCL error, call [CLGetInfoInteger](clgetinfointeger.md), while thehandleparameter is ignored (can be set to zero). Description of errors: [https://registry.khronos.org/OpenCL/specs/3.0-unified/html/OpenCL\_API.html#CL\_SUCCESS](https://registry.khronos.org/OpenCL/specs/3.0-unified/html/OpenCL_API.md#CL_SUCCESS).

For an unknown error code, the"unknown OpenCL error N" string is returned where N is an error code. Example:

```
//--- the first 'handle' parameter is ignored when getting the last error code
intcode= (int)CLGetInfoInteger(0,CL_LAST_ERROR);
```

Text description of the OpenCL error: To get the latest OpenCL error, call [CLGetInfoString](clgetinfostring.md). The error code should be passed as thehandleparameter.

Description of errors: [https://registry.khronos.org/OpenCL/specs/3.0-unified/html/OpenCL\_API.html#CL\_SUCCESS](https://registry.khronos.org/OpenCL/specs/3.0-unified/html/OpenCL_API.md#CL_SUCCESS). If CL\_LAST\_ERROR is passed instead of the error code, then the function returns the description of the last error. For example:

```
//--- get the code of the last OpenCL error
int   code= (int)CLGetInfoInteger(0,CL_LAST_ERROR);
stringdesc;// to get an error text description
 
//--- use the error code to get an error text description
if(!CLGetInfoString(code,CL_ERROR_DESCRIPTION,desc))
 desc="cannot get OpenCL error description,"+ (string)GetLastError();
Print(desc);
 
//--- in order to get the description of the last OpenCL error without getting the code first, pass CL_LAST_ERROR  
if(!CLGetInfoString(CL_LAST_ERROR,CL_ERROR_DESCRIPTION,desc))
 desc="cannot get OpenCL error description,"+ (string)GetLastError();
Print(desc);;
```

So far, the name of the internal enumeration is given as an error description. You can find its decoding here: [https://registry.khronos.org/OpenCL/specs/3.0-unified/html/OpenCL\_API.html#CL\_SUCCESS](https://registry.khronos.org/OpenCL/specs/3.0-unified/html/OpenCL_API.md#CL_SUCCESS). For example, the CL\_INVALID\_KERNEL\_ARGS value means "Returned when enqueuing a kernel when some kernel arguments have not been set or are invalid."

Functions for running programs in OpenCL:

| Function | Action |
| --- | --- |
| [CLHandleType](clhandletype.md) | Returns the type of an OpenCL handle as a value of the ENUM\_OPENCL\_HANDLE\_TYPE enumeration |
| [CLGetInfoInteger](clgetinfointeger.md) | Returns the value of an integer property for an OpenCL object or device |
| [CLContextCreate](clcontextcreate.md) | Creates an OpenCL context |
| [CLContextFree](clcontextfree.md) | Removes an OpenCL context |
| [CLGetDeviceInfo](clgetdeviceinfo.md) | Receives device property from OpenCL driver |
| [CLProgramCreate](clprogramcreate.md) | Creates an OpenCL program from a source code |
| [CLProgramFree](clprogramfree.md) | Removes an OpenCL program |
| [CLKernelCreate](clkernelcreate.md) | Creates an OpenCL start function |
| [CLKernelFree](clkernelfree.md) | Removes an OpenCL start function |
| [CLSetKernelArg](clsetkernelarg.md) | Sets a parameter for the OpenCL function |
| [CLSetKernelArgMem](clsetkernelargmem.md) | Sets an OpenCL buffer as a parameter of the OpenCL function |
| [CLSetKernelArgMemLocal](clsetkernelargmemlocal.md) | Sets the local buffer as an argument of the kernel function |
| [CLBufferCreate](clbuffercreate.md) | Creates an OpenCL buffer |
| [CLBufferFree](clbufferfree.md) | Deletes an OpenCL buffer |
| [CLBufferWrite](clbufferwrite.md) | Writes an array into an OpenCL buffer |
| [CLBufferRead](clbufferread.md) | Reads an OpenCL buffer into an array |
| [CLExecute](clexecute.md) | Runs an OpenCL program |
| [CLExecutionStatus](clexecutionstatus.md) | Returns the OpenCL program execution status |

See also

[OpenCL](copencl.md), [Resources](resources.md#resourcevariables)