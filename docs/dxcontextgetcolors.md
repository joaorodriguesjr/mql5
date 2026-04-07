DXContextGetColors



[MQL5 Reference](index.md)  /  [Working with DirectX](directx.md) / DXContextGetColors

[![Previous](previous.png)](dxcontextcleardepth.md) 
[![Next](next.png)](dxcontextgetdepth.md)

DXContextGetColors

Gets an image of a specified size and offset from a graphic context.

```
bool  DXContextGetColors(
   int    context,                       // graphic context handle   
   uint&  image[],                       // image pixels array 
   int    image_width=WHOLE_ARRAY,       // image width in pixels
   int    image_height=WHOLE_ARRAY,      // image height in pixels
   int    image_offset_x=0,              // X offset
   int    image_offset_y=0               // Y offset
   );
```

Parameters

context

[in]  Handle for a graphic context created in [DXContextCreate()](dxcontextcreate.md).

image

[out]  The array of image\_width*image\_height pixels in [ARGB](colortoargb.md) format.

image\_width=WHOLE\_ARRAY

[in]  Image width in pixels.

image\_height=WHOLE\_ARRAY

[in]  Image height in pixels.

image\_offset\_x=0

[in]  X offset.

image\_offset\_y=0

[in]  Y offset.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.