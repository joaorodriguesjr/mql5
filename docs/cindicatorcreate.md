Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / Create

[![Previous](previous.png)](cindicatorfullrelease.md) 
[![Next](next.png)](cindicatorbufferresize.md)

Create

Creates the indicator of the specified type with the specified parameters.

```
bool  Create(
   const string           symbol,         // symbol
   const ENUM_TIMEFRAMES  period,         // period
   const ENUM_INDICATOR   type,           // type
   const int              num_params,     // number of parameters
   const MqlParam&        params[]        // array of parameters
   )
```

Parameters

symbol

[in]  Indicator symbol.

period

[in]  Indicator timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration).

type

[in]  Indicator type ([ENUM\_INDICATOR](enum_indicator.md) enumeration).

num\_params

[in]  Number of indicator's parameters.

params

[in]  Reference to the parameters array for the indicator.

Return Value

true - successful, false - cannot create the indicator.