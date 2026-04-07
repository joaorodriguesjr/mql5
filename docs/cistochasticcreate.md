Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Oscillators](oscillatorindicators.md)  /  [CiStochastic](cistochastic.md) / Create

[![Previous](previous.png)](cistochasticpricefield.md) 
[![Next](next.png)](cistochasticmain.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,          // symbol
   ENUM_TIMEFRAMES  period,          // period
   int              Kperiod,         // %K period
   int              Dperiod,         // %D period
   int              slowing,         // slowing period
   ENUM_MA_METHOD   ma_method,       // averaging method
   ENUM_STO_PRICE   price_field      // application
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

Kperiod

[in]  Averaging period of %K indicator.

Dperiod

[in]  Averaging period of %D indicator.

slowing

[in]  Slowing period.

ma\_method

[in]  Averaging method ([ENUM\_MA\_METHOD](enum_ma_method.md) enumeration value).

price\_field

[in]  Object (Low/High or Close/Close) to apply ([ENUM\_STO\_PRICE](prices.md) enumeration value).

Return Value

true - successful, false - cannot create the indicator.