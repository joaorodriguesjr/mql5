Attach



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / Attach

[![Previous](previous.png)](ccanvas.md) 
[![Next](next.png)](ccanvasarc.md)

Attach

Gets the graphical resource from an [OBJ\_BITMAP\_LABEL](obj_bitmap_label.md) object and attaches it to an instance of the CCanvas class.

```
bool  Attach(
   const long         chart_id,                              // chart identifier
   const string       objname,                               // object name
   ENUM_COLOR_FORMAT  clrfmt=COLOR_FORMAT_XRGB_NOALPHA       // color processing method
```

Creates a graphical [resource](resources.md) for an [OBJ\_BITMAP\_LABEL](obj_bitmap_label.md) object and attaches it to an instance of the CCanvas class.

```
bool  Attach(
   const long         chart_id,                              // chart identifier
   const string       objname,                               // object name
   const int          width,                                 // image width in pixels
   const int          height,                                // image height in pixels
   ENUM_COLOR_FORMAT  clrfmt=COLOR_FORMAT_XRGB_NOALPHA       // color processing method
```

 

Parameters

chart\_id

[out]  Chart identifier.

objname

[in]  Name of the graphical object.

width

[in]  Image width in the resource.

height

[in]  Image height in the resource.

clrfmt=COLOR\_FORMAT\_XRGB\_NOALPHA

[in]  Alpha channel processing method. The alpha channel is ignored by default.

Return Value

true if successful, false - if failed to attach the object.