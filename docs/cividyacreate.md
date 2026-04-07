Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md)  /  [CiVIDyA](cividya.md) / Create

[![Previous](previous.png)](cividyaapplied.md) 
[![Next](next.png)](cividyamain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,         // symbol
   ENUM_TIMEFRAMES  period,         // period
   int              cmo_period,     // momentum period
   int              ema_period,     // averaging period
   int              ind_shift,      // shift
   int              applied         // price type, handle
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

cmo\_period

[in]  Momentum period.

ema\_period

[in]  Averaging period.

ind\_shift

[in]  Horizontal shift.

applied

[in]  Price type or handle to apply.

Return Value

true - successful, false - cannot create the indicator.