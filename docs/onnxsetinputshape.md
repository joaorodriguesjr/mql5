OnnxSetInputShape



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxSetInputShape

[![Previous](previous.png)](onnxgetoutputtypeinfo.md) 
[![Next](next.png)](onnxsetoutputshape.md)

OnnxSetInputShape

Set the shape of a model's input data by index.

```
bool  OnnxSetInputShape(
   long          onnx_handle,  // ONNX session handle
   long          input_index,  // input parameter index
   const ulong&  shape[]       // array describing input data shape
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

input\_index

[in]  Index of the input parameter, starting from 0.

shape

[in]  Array describing model's input data shape.

Return Value

Returns the name of the input parameter on success; otherwise returns NULL. To get the [error](errorcodes.md) code, call the [GetLastError](getlasterror.md) function.

 

Example:

```
//---- describe the shapes of the model's input and output data
   const long  ExtOutputShape[] = {1,1};
   const long  ExtInputShape [] = {1,10,4};
//--- create the model
   long handle=OnnxCreateFromBuffer(model,ONNX_DEBUG_LOGS);
//--- specify the shape of the input data
   if(!OnnxSetInputShape(handle,0,ExtInputShape))
     {
      Print("failed, OnnxSetInputShape error ",GetLastError());
      OnnxRelease(handle);
      return(-1);
     }
//--- specify the shape of the output data
   if(!OnnxSetOutputShape(handle,0,ExtOutputShape))
     {
      Print("failed, OnnxSetOutputShape error ",GetLastError());
      OnnxRelease(handle);
      return(-1);
     }
```

See also

[OnnxSetOutputShape](onnxsetoutputshape.md)