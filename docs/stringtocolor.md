StringToColor



[MQL5 Reference](index.md)  /  [Conversion Functions](convert.md) / StringToColor

[![Previous](previous.png)](stringtochararray.md) 
[![Next](next.png)](stringtodouble.md)

StringToColor

Converting "R,G,B" string or string with color name into color type value.

```
color  StringToColor(
   string  color_string      // string representation of color
   );
```

Parameters

color\_string

[in]  String representation of a color of "R,G,B" type or name of one of predefined [Web-colors](webcolors.md).

Return Value

Color value.

 

Example:

```
   color str_color=StringToColor("0,127,0");
   Print(str_color);
   Print((string)str_color);
//--- change color a little
   str_color=StringToColor("0,128,0");
   Print(str_color);
   Print((string)str_color);
```

See also

[ColorToString](colortostring.md), [ColorToARGB](colortoargb.md)