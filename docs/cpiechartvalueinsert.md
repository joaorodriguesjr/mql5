ValueInsert



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CPieChart](cpiechart.md) / ValueInsert

[![Previous](previous.png)](cpiechartvalueadd.md) 
[![Next](next.png)](cpiechartvalueupdate.md)

ValueInsert

Inserts a new value to the pie chart (at the specified position).

```
 bool  ValueInsert(
   const uint    pos,    // index
   const double  value,  // value
   const string  descr,  // label
   const uint    clr,    // color
   )
```

Parameters

pos

[in] Index for insertion.

value

[in] Value.

descr

[in] Value label. 

clr

[in] Value color.

Return Value

true if successful, otherwise false.