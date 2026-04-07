Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md)  /  [CiDEMA](cidema.md) / Create

[![Previous](previous.png)](cidemaapplied.md) 
[![Next](next.png)](cidemamain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           string,        // symbol
   ENUM_TIMEFRAMES  period,        // period
   int              ma_period,     // averaging period
   int              ind_shift,     // shift
   int              applied        // price type, handle
   )
```

Parameters

string

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

ma\_period

[in]  Averaging period.

ind\_shift

[in]  Horizontal shift.

applied

[in]  Price type or handle to apply.

Return Value

true - successful, false - cannot create the indicator.