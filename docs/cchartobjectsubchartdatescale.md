DateScale



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectSubChart](cchartobjectsubchart.md) / DateScale

[![Previous](previous.png)](cchartobjectsubchartscale.md) 
[![Next](next.png)](cchartobjectsubchartpricescale.md)

DateScale (Get Method)

Gets the value of "DateScale" flag.

```
bool  DateScale() const
```

Return Value

Value of "DateScale" flag of the object assigned to the class instance. If there is no object assigned, it returns false.

DateScale (Set Method)

Sets new value for "DateScale" property.

```
bool  DateScale(
   bool  scale      // flag value
   )
```

Parameters

scale

[in]  New value for "DateScale" flag.

Return Value

true - successful, false - cannot change the flag.