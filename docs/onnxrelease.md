OnnxRelease



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxRelease

[![Previous](previous.png)](onnxcreatefrombuffer.md) 
[![Next](next.png)](onnxrun.md)

OnnxRelease

Close an ONNX session.

```
bool  OnnxRelease(
   long   onnx_handle  // ONNX session handle
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

Return Value

Returns true on success; otherwise returns false. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.