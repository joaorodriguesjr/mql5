ShowLastLine



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ShowLastLine

[![Previous](previous.png)](cchartshowlineask.md) 
[![Next](next.png)](cchartshowperiodsep.md)

ShowLastLine (Get Method)

Gets the value of "ShowLastLine" property.

```
bool  ShowLastLine() const
```

Return Value

Value of "ShowLastLine" property of the chart assigned to the class instance. If there is no chart assigned, it returns false.

ShowLastLine (Set Method)

Sets new value for "ShowLastLine" property.

```
bool  ShowLastLine(
   bool  show      // property value
   )
```

Parameters

show

[in]  New value for "ShowLastLine" property.

Return Value

true - successful, false - cannot change the property.