FontSize



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectText](cchartobjecttext.md) / FontSize

[![Previous](previous.png)](cchartobjecttextfont.md) 
[![Next](next.png)](cchartobjecttextanchor.md)

FontSize  (Get Method)

Gets the value of "Font size" property.

```
int  FontSize() const
```

Return Value

Value of "FontSize" property of the object assigned to the class instance. If there is no object assigned, it returns 0.

FontSize (Set Method)

Sets new value for "Font size" property.

```
bool  FontSize(
   int  size      // property value
   )
```

Parameters

size

[in]  New value for "Font size" property.

Return Value

true - successful, false - cannot change the property.