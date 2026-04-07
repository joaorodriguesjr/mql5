OnnxGetInputCount



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxGetInputCount

[![Previous](previous.png)](onnxrun.md) 
[![Next](next.png)](onnxgetoutputcount.md)

OnnxGetInputCount

Get the number of inputs in an ONNX model.

```
long  OnnxGetInputCount(
   long   onnx_handle  // ONNX session handle
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

Return Value

Returns the number of input parameters on success; otherwise returns -1. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.