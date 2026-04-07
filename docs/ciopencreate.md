Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Timeseries classes](timeseries.md)  /  [CiOpen](ciopen.md) / Create

[![Previous](previous.png)](ciopen.md) 
[![Next](next.png)](ciopengetdata.md)

Create

Creates a timeseries with the specified parameters for access to the open prices of the bars in the history.

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