FontGet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / FontGet

[![Previous](previous.png)](ccanvasfontflagsset.md) 
[![Next](next.png)](ccanvasfontnameget.md)

FontGet

Receives the current font parameters.

```
void  FontGet(
   string&  name,      // name
   int&     size,      // size
   uint&    flags,     // flags
   uint&    angle      // slope angle
   );
```

Parameters

name

[out]  Reference to the variable for returning a font name.

size

[out]  Reference to the variable for returning a font size.

flags

[out]  Reference to the variable for returning font flags.

angle

[out]  Reference to the variable for returning a font slope angle.