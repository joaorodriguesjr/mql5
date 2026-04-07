Period



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / Period

[![Previous](previous.png)](cchartsymbol.md) 
[![Next](next.png)](cchartredraw.md)

Period

Gets period of the chart.

```
ENUM_TIMEFRAMES  Period() const
```

Return Value

Period of the chart (from [ENUM\_TIMEFRAMES](enum_timeframes.md)) assigned to the class instance. If there is no chart assigned, it returns 0.