LabelMake



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CPieChart](cpiechart.md) / LabelMake

[![Previous](previous.png)](cpiechartdrawpie.md) 
[![Next](next.png)](3dgraphics.md)

LabelMake

Generates a segment label based on its value and the original label.

```
 string  LabelMake(
   const string  text,     // label
   const double  value,    // value
   const bool    to_left,  // flag
   )
```

Parameters

text

[in] Label.

value

[in] Value. 

to\_left

[in]  Defines the order of the label layout:

* true label, then value.
* false value, then label.

Return Value

Label of the segment.