OnnxGetOutputTypeInfo



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxGetOutputTypeInfo

[![Previous](previous.png)](onnxgetinputtypeinfo.md) 
[![Next](next.png)](onnxsetinputshape.md)

OnnxGetOutputTypeInfo

Get the description of the output type from the model.

```
bool  OnnxGetOutputTypeInfo(
   long           onnx_handle,  // ONNX session handle
   long           index,        // parameter index
   OnnxTypeInfo&  typeinfo      // parameter type description
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

index

[in]  Index of the output parameter, starting with 0.

typeinfo

[out]  The [OnnxTypeInfo](onnx_structures.md#onnxtypeinfo) structure that describes the type of the output parameter.

Return Value

Returns true on success; otherwise returns false. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.