Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Oscillators](oscillatorindicators.md)  /  [CiMACD](cimacd.md) / Create

[![Previous](previous.png)](cimacdapplied.md) 
[![Next](next.png)](cimacdmain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,              // symbol
   ENUM_TIMEFRAMES  period,              // period
   int              fast_ema_period,     // fast EMA period
   int              slow_ema_period,     // slow EMA period
   int              signal_period,       // signal period
   int              applied              // price type, handle
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

fast\_ema\_period

[in]  Fast EMA averaging period.

slow\_ema\_period

[in]  Slow EMA averaging period.

signal\_period

[in]  Signal line averaging period.

applied

[in]  Price type or handle to apply.

Return Value

true - successful, false - cannot create the indicator.