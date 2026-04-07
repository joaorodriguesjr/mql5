AutoScroll



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / AutoScroll

[![Previous](previous.png)](cchartshiftsize.md) 
[![Next](next.png)](cchartscale.md)

AutoScroll (Get Method)

Gets the value of "AutoScroll" property.

```
bool  AutoScroll() const
```

Return Value

Value of "AutoScroll" property of the chart assigned to the class instance. If there is no chart assigned, it returns false.

AutoScroll (Set Method)

Sets new value for "AutoScroll" property.

```
bool  AutoScroll(
   bool  autoscroll      // flag value
   )
```

Parameters

autoscroll

[in]  New value for "Autoscroll" property.

Return Value

true - successful, false - cannot change the property.