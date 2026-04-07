Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Volume Indicators](volumeindicators.md)  /  [CiMFI](cimfi.md) / Create

[![Previous](previous.png)](cimfiapplied.md) 
[![Next](next.png)](cimfimain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string               symbol,        // symbol
   ENUM_TIMEFRAMES      period,        // period
   int                  ma_period,     // averaging period
   ENUM_APPLIED_VOLUME  applied        // volume type
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

ma\_period

[in]  Averaging period.

applied

[in]  Volume type to apply ([ENUM\_APPLIED\_VOLUME](prices.md#enum_applied_volume_enum) enumeration value).

Return Value

true - successful, false - cannot create the indicator.