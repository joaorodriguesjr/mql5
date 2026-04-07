Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md)  /  [CiIchimoku](ciichimoku.md) / Create

[![Previous](previous.png)](ciichimokusenkouspanbperiod.md) 
[![Next](next.png)](ciichimokutenkansen.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,            // symbol
   ENUM_TIMEFRAMES  period,            // period
   int              tenkan_sen,        // period of TenkanSen
   int              kijun_sen,         // period of KijunSen
   int              senkou_span_b      // period of SenkouSpanB
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

tenkan\_sen

[in]  Period of TenkanSen.

kijun\_sen

[in]  Period of KijunSen.

senkou\_span\_b

[in]  Period of SenkouSpanB.

Return Value

true - successful, false - cannot create the indicator.