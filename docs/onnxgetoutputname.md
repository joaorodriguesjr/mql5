OnnxGetOutputName



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxGetOutputName

[![Previous](previous.png)](onnxgetinputname.md) 
[![Next](next.png)](onnxgetinputtypeinfo.md)

OnnxGetOutputName

Get the name of a model's output by index.

```
string  OnnxGetOutputName(
   long   onnx_handle,  // ONNX session handle
   long   index         // parameter index
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

index

[in]  Index of the output parameter, starting with 0.

Return Value

Returns the name of the output parameter on success; otherwise returns NULL. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.