SeriesSet



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CPieChart](cpiechart.md) / SeriesSet

[![Previous](previous.png)](cpiechartcreate.md) 
[![Next](next.png)](cpiechartvalueadd.md)

SeriesSet

Sets a series of values that will be shows on the pie chart.

```
 bool  SeriesSet(
   const double&  value[],  // values
   const string&  text[],   // labels
   const uint&    clr[],    // color
   )
```

Parameters

value[]

[in] Array of values.

text[]

[in] Array of value labels.

clr[]

[in] Array of value colors.

Return Value

true if successful, otherwise false.