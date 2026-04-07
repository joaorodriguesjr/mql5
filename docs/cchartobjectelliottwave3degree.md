Degree



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Elliott Tools](obj_elliott.md)  /  [CChartObjectElliottWave3](cchartobjectelliottwave3.md) / Degree

[![Previous](previous.png)](cchartobjectelliottwave3create.md) 
[![Next](next.png)](cchartobjectelliottwave3lines.md)

Degree (Get Method)

Gets the value of "Degree" property.

```
ENUM_ELLIOT_WAVE_DEGREE  Degree() const
```

Return Value

Value of "Degree" property of the object assigned to the class instance. If there is no object assigned, it returns WRONG\_VALUE.

Degree (Set Method)

Sets new value for "Degree" property.

```
bool  Degree(
   ENUM_ELLIOT_WAVE_DEGREE  degree      // property value
   )
```

Parameters

degree

[in]  New value for "Degree" property.

Return Value

true - successful, false - cannot change the property.