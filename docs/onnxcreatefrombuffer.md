OnnxCreateFromBuffer



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxCreateFromBuffer

[![Previous](previous.png)](onnxcreate.md) 
[![Next](next.png)](onnxrelease.md)

OnnxCreateFromBuffer

Create an ONNX session, loading a model from a data array.

```
long  OnnxCreateFromBuffer(
   const uchar&  buffer[],   // array reference
   ulong         flags       // model creation flags
   );
```

Parameters

buffer

[in] Array with ONNX model data.

flags

[in] Flags from [ENUM\_ONNX\_FLAGS](onnx_structures.md#enum_onnx_flags), describing the model creation mode: ONNX\_COMMON\_FOLDER and ONNX\_DEBUG\_LOGS.

Return Value

The handle of the created session or INVALID\_HANDLE if error occurs. To obtain the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.