Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Bill Williams Indicators](bwindicators.md)  /  [CiFractals](cifractals.md) / Create

[![Previous](previous.png)](cifractals.md) 
[![Next](next.png)](cifractalsupper.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,     // symbol
   ENUM_TIMEFRAMES  period      // period
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

Return Value

true - successful, false - cannot create the indicator.