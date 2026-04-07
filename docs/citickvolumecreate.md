Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Timeseries classes](timeseries.md)  /  [CiTickVolume](citickvolume.md) / Create

[![Previous](previous.png)](citickvolume.md) 
[![Next](next.png)](citickvolumebufferresize.md)

Create

Creates a timeseries with the specified parameters for access to the tick volumes of the bars in the history.

```
bool  Create(
   string           symbol,     // symbol
   ENUM_TIMEFRAMES  period      // period
   )
```

Parameters

symbol

[in]  Timeseires symbol.

period

[in]  Timeseries timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

Return Value

true - successful, false - cannot create a timeseries.