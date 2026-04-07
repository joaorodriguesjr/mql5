OnnxSetOutputShape



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / OnnxSetOutputShape

[![Previous](previous.png)](onnxsetinputshape.md) 
[![Next](next.png)](onnx_structures.md)

OnnxSetOutputShape

Set the shape of a model's output data by index.

```
bool  OnnxSetOutputShape(
   long          onnx_handle,   // ONNX session handle
   long          output_index,  // output parameter index
   const ulong&  shape[]        // array describing output data shape
   );
```

Parameters

onnx\_handle

[in]  ONNX session object handle created via [OnnxCreate](onnxcreate.md) or [OnnxCreateFromBuffer](onnxcreatefrombuffer.md).

output\_index

[in]  Index of the output parameter, starting from 0.

shape

[in]  Array describing model's output data shape.

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

[OnnxSetInputShape](onnxsetinputshape.md)