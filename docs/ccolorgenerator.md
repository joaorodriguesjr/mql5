CColorGenerator



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Scientific Charts](graphics.md) / CColorGenerator

[![Previous](previous.png)](caxisselectaxisscale.md) 
[![Next](next.png)](ccolorgeneratornext.md)

CColorGenerator

CColorGenerator class is an auxiliary graphics library class for working with the color palette.

Description

The CColorGenerator class contains the initial color palette used for curves by default (if a color is not specified by a user).

If all colors from the initial palette are used already, new colors are automatically generated and the palette is refilled.

Declaration

```
   class CColorGenerator
```

Title

```
   #include <Graphics\ColorGenerator.mqh>
```

Class methods

| Method | Description |
| --- | --- |
| [Next](ccolorgeneratornext.md) | Returns the next color from the palette |
| [Reset](ccolorgeneratorreset.md) | Resets the generator |