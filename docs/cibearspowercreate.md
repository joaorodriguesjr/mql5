Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Oscillators](oscillatorindicators.md)  /  [CiBearsPower](cibearspower.md) / Create

[![Previous](previous.png)](cibearspowermaperiod.md) 
[![Next](next.png)](cibearspowermain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,        // symbol
   ENUM_TIMEFRAMES  period,        // period
   int              ma_period      // averaging period
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

ma\_period

[in]  Averaging period.

Return Value

true - successful, false - cannot create the indicator.