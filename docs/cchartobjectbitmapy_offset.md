Y\_Offset



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md)  /  [CChartObjectBitmap](cchartobjectbitmap.md) / Y\_Offset

[![Previous](previous.png)](cchartobjectbitmapx_offset.md) 
[![Next](next.png)](cchartobjectbitmapsave.md)

Y\_Offset (Get Method)

Gets the value of "Y\_Offset" property (the upper left corner) of the [CChartObjectBitmap](cchartobjectbitmap.md) graphical object.

```
int  Y_Offset() const
```

Return Value

Value of "Y\_Offset" property of the object assigned to the class instance. If there is no object assigned, it returns 0.

Y\_Offset (Set Method)

Sets new value for "Y\_Offset" property (the upper left corner) of the [CChartObjectBitmap](cchartobjectbitmap.md) graphical object. The value is set in pixels relative to the upper left corner of the original image.

```
bool  Y_Offset(
   int  Y      // property value
   )
```

Parameters

Y

[in]  New value for "Y\_Offset" property.

Return Value

true - successful, false - cannot change the property.