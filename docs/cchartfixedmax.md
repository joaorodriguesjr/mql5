FixedMax



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / FixedMax

[![Previous](previous.png)](cchartscalefix_11.md) 
[![Next](next.png)](cchartfixedmin.md)

FixedMax (Get Method)

Gets the value of "FixedMax" property (fixed maximal price).

```
double  FixedMax() const
```

Return Value

Value of "FixedMax" property of the chart assigned to the class instance. If there is no chart assigned, it returns [EMPTY\_VALUE](otherconstants.md).

FixedMax (Set Method)

Sets the new value for "FixedMax" property.

```
bool  FixedMax(
   double  max      // fixed maximum
   )
```

Parameters

max

[in]  New value for "FixedMax" property.

Return Value

true - successful, false - cannot change the property.