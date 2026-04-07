FixedMin



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / FixedMin

[![Previous](previous.png)](cchartfixedmax.md) 
[![Next](next.png)](cchartpointsperbar.md)

FixedMin (Get Method)

Gets the value of "FixedMin" property (fixed minimal price).

```
double  FixedMin() const
```

Return Value

Value of "FixedMin" property of the chart assigned to the class instance. If there is no chart assigned, it returns [EMPTY\_VALUE](otherconstants.md).

FixedMin (Set Method)

Sets new value for "FixedMin" property.

```
bool  FixedMax(
   double  min      // fixed minimum
   )
```

Parameters

max

[in]  New value for "FixedMin" property.

Return Value

true - successful, false - cannot change the property.