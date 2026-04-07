BorderType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectRectLabel](cchartobjectrectlabel.md) / BorderType

[![Previous](previous.png)](cchartobjectrectlabelangle.md) 
[![Next](next.png)](cchartobjectrectlabelsave.md)

BorderType

Gets border type property value.

```
int  BorderType() const
```

Return Value

Border type property value of the object assigned to the class instance. If there is no object assigned, it returns 0.

BorderType

Sets border type property value.

```
bool  BorderType(
   int  type      // property value
   )
```

Parameters

type

[in]  New border type property value.

Return Value

true - successful, false - cannot change the property.