Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md)  /  [CiEnvelopes](cienvelopes.md) / Create

[![Previous](previous.png)](cienvelopesapplied.md) 
[![Next](next.png)](cienvelopesupper.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,        // symbol
   ENUM_TIMEFRAMES  period,        // period
   int              ma_period,     // averaging period
   int              ma_shift,      // shift
   ENUM_MA_METHOD   ma_method,     // averaging method
   int              applied,       // price type, handle
   double           deviation      // deviation
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

[in]  Price axis shift.

ma\_method

[in]  Averaging method ([ENUM\_MA\_METHOD](enum_ma_method.md) enumeration value).

applied

[in]  Object (price type or handle) to apply.

deviation

[in]  Deviation.

Return Value

true - successful, false - cannot create the indicator.