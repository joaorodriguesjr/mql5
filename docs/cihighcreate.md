Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Timeseries classes](timeseries.md)  /  [CiHigh](cihigh.md) / Create

[![Previous](previous.png)](cihigh.md) 
[![Next](next.png)](cihighgetdata.md)

Create

Creates a timeseries with the specified parameters for access to the high prices of the bars in the history.

```
bool  Create(
   string           symbol,     // symbol
   ENUM_TIMEFRAMES  period      // period
   )
```

Parameters

symbol

[in]  Timeseries symbol.

period

[in]  Timeseries timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

Return Value

true - successful, false - cannot create a timeseries.