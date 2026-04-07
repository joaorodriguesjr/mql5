OnnxGetInputName



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxGetInputName

[![Previous](previous.png)](onnxgetoutputcount.md) 
[![Next](next.png)](onnxgetoutputname.md)

OnnxGetInputName

Get the name of a model's input by index.

```
string  OnnxGetInputName(
   long   onnx_handle,  // ONNX session handle
   long   index         // parameter index
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

index

[in]  Index of the input parameter, starting with 0.

Return Value

Returns the name of the input parameter on success; otherwise returns NULL. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.