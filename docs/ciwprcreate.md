Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Oscillators](oscillatorindicators.md)  /  [CiWPR](ciwpr.md) / Create

[![Previous](previous.png)](ciwprcalcperiod.md) 
[![Next](next.png)](ciwprmain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,          // symbol
   ENUM_TIMEFRAMES  period,          // period
   int              calc_period      // calculation period
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

calc\_period

[in]  Period for calculation.

Return Value

true - successful, false - cannot create the indicator.