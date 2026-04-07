PipsPerBar



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Gann Tools](obj_gann.md)  /  [CChartObjectGannGrid](cchartobjectganngrid.md) / PipsPerBar

[![Previous](previous.png)](cchartobjectganngridcreate.md) 
[![Next](next.png)](cchartobjectganngriddowntrend.md)

PipsPerBar (Get Method)

Gets the value of "Pips per bar" property.

```
double  PipsPerBar() const
```

Return Value

Value of "Pips per bar" property of the object assigned to the class instance. If there is no object assigned, it returns [EMPTY\_VALUE](otherconstants.md).

PipsPerBar (Set Method)

Sets new value for "Pips per bar" property.

```
bool  PipsPerBar(
   double  ppb      // Pips per bar
   )
```

Parameters

ppb

[in]  New value for "Pips per bar" property.

Return Value

true - successful, false - cannot change the property.