ColorToPRGB



[MQL5 Reference](index.md)  /  [Conversion Functions](convert.md) / ColorToPRGB

[![Previous](previous.png)](colortoargb.md) 
[![Next](next.png)](colortostring.md)

ColorToPRGB

Converts the type [color](color.md) in type [uint](integertypes.md#uint) to get premultiplied ARGB representation of color - PRGB. PRGB color format is used when creating [graphic resource](resources.md), [text output](textout.md) and in the CCanvas standard library class with the color format [COLOR\_FORMAT\_ARGB\_RAW](resourcecreate.md#enum_color_format)  (components are not processed by the terminal and must be correctly prepared by the user).

```
uint  ColorToPRGB(
   color  clr,          // converted color in color format
   uchar  alpha=255     // alpha channel that controls color transparency
   );
```

Parameters

clr

[in] Value of color in a variable of type color.

alpha

[in] Value of alpha channel, to get color in format [ARGB](resourcecreate.md). It is set from 0 (the color of the superimposed pixel does not change the display of the underlying pixel at all) to 255 (the color is superimposed completely and overlaps the color of the underlying pixel). Color transparency in percentage terms is calculated as (1-alpha/255)*100%, i.e. the lower the alpha channel value, the more transparent the color is.

Return value

Color representation in ARGB format, where four bytes of uint type contain the values Alfa, Red, Green, Blue (alpha channel, red, green, blue).

Note

How does PRGB differ from ARGB?

There are two common representations of RGBA color with an alpha channel:

* straight (normal) ARGB - RGB is stored "as is", alpha is separate;
* premultiplied (PRGB) - RGB is already multiplied by alpha.

Mode [COLOR\_FORMAT\_ARGB\_RAW](resourcecreate.md#enum_color_format) assumes that color components are already correctly prepared and the terminal does not "normalize/recalculate" them. Therefore, in scenarios where premultiplied-color is expected, it is PRGB that should be passed, otherwise visual artifacts/mismatches during rendering may occur.

PRGB color is calculated by the formula:

```
R = R * A / 255
```

```
G = G * A / 255
```

```
B = B * A / 255
```

```
A = A
```

Special Cases:

* when alpha = 255 the result coincides with ColorToARGB(clr,255) (multiplication does not change RGB);
* when alpha = 0 the result becomes 0x00000000 (fully transparent pixel, RGB = 0).

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
{
   uchar alpha = 0x55; // 0x55 = 85; transparency ~ (255-85)/255 * 100% = 66.7%
   color c = clrWhite;
 
   PrintFormat("0x%%.8X - %s", c, ColorToString(c,true));
   PrintFormat("0x%.8X - ARGB (straight)", ColorToARGB(c, alpha));
   PrintFormat("0x%.8X - PRGB (premultiplied)", ColorToPRGB(c, alpha));
   /*
   0x00FFFFFF - clrWhite
   0x55FFFFFF - ARGB (straight)
   0x55555555 - PRGB (premultiplied)
   */
}
```

See also

[Resources](resources.md), [ColorToARGB](colortoargb.md), [ResourceCreate()](resourcecreate.md), [TextOut()](textout.md), [Color type](color.md), [Types char, short, int and long](integertypes.md)