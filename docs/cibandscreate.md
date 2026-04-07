Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md)  /  [CiBands](cibands.md) / Create

[![Previous](previous.png)](cibandsapplied.md) 
[![Next](next.png)](cibandsbase.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,        // symbol
   ENUM_TIMEFRAMES  period,        // period
   int              ma_period,     // averaging period
   int              ma_shift,      // shift
   double           deviation,     // deviation
   int              applied        // applied price, handle
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

ma\_period

[in]  Averaging period.

ma\_shift

[in]  Horizontal shift of the indicator.

deviation

[in]  Deviation.

applied

[in]  Price type or handle to apply.

Return Value

true - successful, false - cannot create the indicator.