PriceScale



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectSubChart](cchartobjectsubchart.md) / PriceScale

[![Previous](previous.png)](cchartobjectsubchartdatescale.md) 
[![Next](next.png)](cchartobjectsubcharttime.md)

PriceScale (Get Method)

Gets the value of "PriceScale" flag.

```
bool  PriceScale() const
```

Return Value

Value of "PriceScale" flag of the object assigned to the class instance. If there is no object assigned, it returns false.

PriceScale (Set Method)

Sets new value for "PriceScale" flag.

```
bool  PriceScale(
   bool  scale      // flag value
   )
```

Parameters

scale

[in]  New value for "PriceScale" flag.

Return Value

true - successful, false - cannot change the flag.