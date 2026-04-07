PeriodDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CSeries](cseries.md) / PeriodDescription

[![Previous](previous.png)](cseriesrefresh.md) 
[![Next](next.png)](cpriceseries.md)

PeriodDescription

Gets the string representation of the specified [ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration.

```
string  PeriodDescription(
   const int  val=0      // value
   )
```

Parameters

val=0

[in]  Value to convert.

Return Value

The string representation of the specified [ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration.

Note

If the value is not specified or equal to zero,the timeframe of timeseries or indicator is transformed into a string.