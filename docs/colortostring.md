ColorToString



[MQL5 Reference](index.md)  /  [Conversion Functions](convert.md) / ColorToString

[![Previous](previous.png)](colortoprgb.md) 
[![Next](next.png)](doubletostring.md)

ColorToString

It converts color value into string of "R,G,B" form.

```
string  ColorToString(
   color  color_value,     // color value
   bool   color_name       // show color name or not
   );
```

Parameters

color\_value

[in]  Color value in color type variable.

color\_name

[in]  Return color name if it is identical to one of predefined [color constants](webcolors.md).

Return Value

String presentation of color as "R,G,B", where R, G and B are decimal constants from 0 to 255 converted into a string. If the color\_name=true parameter is set, it will try to convert color value into color name.

 

Example:

```
   string clr=ColorToString(C'0,255,0'); // green color
   Print(clr);
 
   clr=ColorToString(C'0,255,0',true);   // get color constant
   Print(clr);
```

See also

[StringToColor](stringtocolor.md), [ColorToARGB](colortoargb.md)