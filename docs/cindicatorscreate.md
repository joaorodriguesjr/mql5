Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicators](cindicators2.md) / Create

[![Previous](previous.png)](cindicators2.md) 
[![Next](next.png)](cindicatorsrefresh.md)

Create

Creates the indicator of the specified type with the specified parameters.

```
CIndicator*  Create(
   const string           symbol,     // symbol name
   const ENUM_TIMEFRAMES  period,     // period
   const ENUM_INDICATOR   type,       // type
   const int              count,      // number of parameters
   const MqlParam&        params      // parameters array
   )
```

Parameters

symbol

[in]  Indicator symbol name.

period

[in]  Indicator timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

type

[in]  Indicator type ([ENUM\_INDICATOR](enum_indicator.md) enumeration value).

count

[in]  Number of parameters for the indicator.

params

[in]  Reference to the parameters array for the indicator.

Return Value

Reference to the created indicator - successful, [NULL](void.md) - cannot create the indicator.