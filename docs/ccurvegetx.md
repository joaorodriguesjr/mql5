GetX



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Scientific Charts](graphics.md)  /  [CCurve](ccurve.md) / GetX

[![Previous](previous.png)](ccurvepointscolor.md) 
[![Next](next.png)](ccurvegety.md)

GetX

Gets X values of all curve dots to the array.

```
void  GetX(
   double&  x[]      // array for writing X values
   )
```

Parameters

x[]

[out]  Array for getting X values of all curve dots.

Note

Each curve dot is defined by a couple of X and Y values. These values are not coordinates in pixels for drawing in the [CGraphic](cgraphic.md) class.