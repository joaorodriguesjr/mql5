ScaleFix



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ScaleFix

[![Previous](previous.png)](cchartscale.md) 
[![Next](next.png)](cchartscalefix_11.md)

ScaleFix (Get Method)

Gets the value of "ScaleFix" property (fixed chart scale or not).

```
bool  ScaleFix() const
```

Return Value

Value of "ScaleFix" property of the chart assigned to the class instance. If there is no chart assigned, it returns false.

ScaleFix (Set Method)

Sets new value for "ScaleFix" property.

```
bool  ScaleFix(
   bool  scale_fix      // property value
   )
```

Parameters

scale\_fix

[in]  New value for "ScaleFix" property.

Return Value

true - successful, false - cannot change the property.