Foreground



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / Foreground

[![Previous](previous.png)](cchartmode.md) 
[![Next](next.png)](cchartshift.md)

Foreground (Get Method)

Gets the value of "Foreground" property.

```
bool  Foreground() const
```

Return Value

Value of "Foreground" property of the chart assigned to the class instance. If there is no chart assigned, it returns false.

Foreground (Set Method)

Sets new value for "Foreground" property.

```
bool  Foreground(
   bool  foreground      // flag value
   )
```

Parameters

foreground

[in]  New value for "Foreground" property.

Return Value

true - successful, false - cannot change the property.