Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md)  /  [CiSAR](cisar.md) / Create

[![Previous](previous.png)](cisarmaximum.md) 
[![Next](next.png)](cisarmain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,      // symbol
   ENUM_TIMEFRAMES  period,      // period
   double           step,        // step
   double           maximum      // coefficient
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

step

[in]  Step for the velocity increasing.

maximum

[in]  Price following coefficient.

Return Value

true - successful, false - cannot change the indicator.