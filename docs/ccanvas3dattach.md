Attach



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [3D Graphics](3dgraphics.md)  /  [CCanvas3D](ccanvas3d.md) / Attach

[![Previous](previous.png)](ccanvas3dambientcolorset.md) 
[![Next](next.png)](ccanvas3dcreate.md)

Attach

Gets the graphical resource from an [OBJ\_BITMAP\_LABEL](obj_bitmap_label.md) object and attaches it to an instance of the CCanvas class.

```
bool  Attach(
   const long         chart_id,                              // chart ID
   const string       objname,                               // object name
   ENUM_COLOR_FORMAT  clrfmt=COLOR_FORMAT_XRGB_NOALPHA       // color handling method 
   )
```

Creates a graphical [resource](resources.md) for an [OBJ\_BITMAP\_LABEL](obj_bitmap_label.md) object and attaches it to an instance of the CCanvas class.

```
bool  Attach(
   const long         chart_id,                              // chart ID
   const string       objname,                               // object name
   const int          width,                                 // image width in pixels
   const int          height,                                // image height in pixels
   ENUM_COLOR_FORMAT  clrfmt=COLOR_FORMAT_XRGB_NOALPHA       // color handling method 
   )
```

Parameters

chart\_id

[in]  Chart ID.

objname

[in]  Name of the graphical object.

width

[in]  Frame width in a resource.

height

[in]  Frame height.

clrfmt=COLOR\_FORMAT\_XRGB\_NOALPHA

[in]  Color handling method. See [ResourceCreate()](resourcecreate.md) function description to learn more about color handling methods.

Note

true if successful, false - if failed to add a graphic object.