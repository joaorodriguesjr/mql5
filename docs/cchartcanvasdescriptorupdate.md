DescriptorUpdate



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md)  /  [CChartCanvas](cchartcanvas.md) / DescriptorUpdate

[![Previous](previous.png)](cchartcanvasvscaleparams.md) 
[![Next](next.png)](cchartcanvascolorupdate.md)

DescriptorUpdate

Updates the value of the series descriptor (at the specified position).

```
 bool  DescriptorUpdate(
   const uint    pos,    // index
   const string  descr,  // value
   )
```

Parameters

pos

[in] Index of the series the serial number of its addition, starting with 0.

descr

[in] Descriptor value.

Return Value

true if successful, otherwise false.