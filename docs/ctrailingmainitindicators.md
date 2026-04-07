InitIndicators



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md)  /  [CTrailingMA](ctrailingma.md) / InitIndicators

[![Previous](previous.png)](ctrailingmaapplied.md) 
[![Next](next.png)](ctrailingmavalidationsettings.md)

InitIndicators

Initializes indicators and timeseries.

```
virtual bool  InitIndicators(
   CIndicators*  indicators      // pointer
   )
```

Parameters

indicators

[in]  Pointer to indicators and timeseries collection ([CExpert](cexpert.md) class member).

Return Value

true - successful, otherwise - false.