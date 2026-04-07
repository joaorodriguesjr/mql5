InitIndicators



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / InitIndicators

[![Previous](previous.png)](cexpertbasesetotherseries.md) 
[![Next](next.png)](cexpertbaseinitopen.md)

InitIndicators

Initializes all indicators and time series.

```
virtual bool  InitIndicators(
   CIndicators*  indicators=NULL    // pointer
   )
```

Parameters

indicators

[in]  Pointer to collection of indicators and timeseries.

Return Value

true - successful, otherwise - false.

Note

The timeseries are initialized only if the object uses the symbol or timeframe different from the symbol or timeframe defined at initialization.