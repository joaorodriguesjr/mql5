TextSize



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CCanvas](ccanvas.md) / TextSize

[![Previous](previous.png)](ccanvastextout.md) 
[![Next](next.png)](ccanvastextwidth.md)

TextSize

Receives the text size.

```
void  TextSize(
   const string  text,       // text
   int&          width,      // width
   int&          height      // height
   );
```

Parameters

text

[in]  Text for measuring.

width

[out]  Reference to the variable for returning a text width.

height

[out]  Reference to the variable for returning a text height.

Note

The current font is used to measure the text.