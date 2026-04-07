Anchor



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectText](cchartobjecttext.md) / Anchor

[![Previous](previous.png)](cchartobjecttextfontsize.md) 
[![Next](next.png)](cchartobjecttextsave.md)

Anchor (Get Method)

Gets the value of "Anchor" property.

```
ENUM_ANCHOR_POINT  Anchor() const
```

Return Value

Value of "Anchor" property of the object assigned to the class instance. If there is no object assigned, it returns WRONG\_VALUE.

Anchor (Set Method)

Sets new value for "Anchor" property.

```
bool  Anchor(
   ENUM_ANCHOR_POINT  anchor      // property value
   )
```

Parameters

anchor

[in]  New value for "Anchor" property.

Return Value

true - success, false - cannot change the property.