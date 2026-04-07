Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Oscillators](oscillatorindicators.md)  /  [CiChaikin](cichaikin.md) / Create

[![Previous](previous.png)](cichaikinapplied.md) 
[![Next](next.png)](cichaikinmain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string               symbol,             // symbol
   ENUM_TIMEFRAMES      period,             // period
   int                  fast_ma_period,     // fast EMA period
   int                  slow_ma_period,     // slow EMA period
   ENUM_MA_METHOD       ma_method,          // averaging method
   ENUM_APPLIED_VOLUME  applied             // volume type
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

fast\_ma\_period

[in]  Period for fast EMA.

slow\_ma\_period

[in]  Period for slow EMA.

ma\_method

[in]  Averaging method ([ENUM\_MA\_METHOD](enum_ma_method.md) enumeration value).

applied

[in]  Object (volume type) to apply ([ENUM\_APPLIED\_VOLUME](prices.md#enum_applied_volume_enum) enumeration value).

Return Value

true - successful, false - cannot create the indicator.