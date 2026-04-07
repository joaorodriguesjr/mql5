Deviations



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Channel Objects](obj_channels.md)  /  [CChartObjectStdDevChannel](cchartobjectstddevchannel.md) / Deviations

[![Previous](previous.png)](cchartobjectstddevchannelcreate.md) 
[![Next](next.png)](cchartobjectstddevchannelsave.md)

Deviation (Get Method)

Gets "Deviation" property value.

```
double  Deviation() const
```

Return Value

Value of "Deviation" property assigned to the class instance. If there is no object assigned, it returns [EMPTY\_VALUE](otherconstants.md).

Deviation (Set Method)

Sets "Deviation" property value.

```
bool  Deviation(
   double  deviation      // deviation
   )
```

Parameters

deviation

[in]  New value for "Deviation" property.

Return Value

true - successful, false - cannot change the property.