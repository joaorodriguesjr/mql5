OnnxGetInputTypeInfo



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxGetInputTypeInfo

[![Previous](previous.png)](onnxgetoutputname.md) 
[![Next](next.png)](onnxgetoutputtypeinfo.md)

OnnxGetInputTypeInfo

Get the description of the input type from the model.

```
bool  OnnxGetInputTypeInfo(
   long           onnx_handle,  // ONNX session handle
   long           index,        // parameter index
   OnnxTypeInfo&  typeinfo      // parameter type description
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

index

[in]  Index of the input parameter, starting with 0.

typeinfo

[out]  The [OnnxTypeInfo](onnx_structures.md#onnxtypeinfo) structure that describes the type of the input parameter.

Return Value

Returns true on success; otherwise returns false. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.