OnnxGetOutputCount



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxGetOutputCount

[![Previous](previous.png)](onnxgetinputcount.md) 
[![Next](next.png)](onnxgetinputname.md)

OnnxGetOutputCount

Get the number of outputs in an ONNX model.

```
long  OnnxGetOutputCount(
   long   onnx_handle  // ONNX session handle
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

Return Value

Returns the number of output parameters on success; otherwise returns -1. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.