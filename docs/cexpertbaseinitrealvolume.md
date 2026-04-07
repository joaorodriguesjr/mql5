InitRealVolume



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / InitRealVolume

[![Previous](previous.png)](cexpertbaseinittickvolume.md) 
[![Next](next.png)](cexpertbasepricelevelunit.md)

InitRealVolume

Initalizes the RealVolume timeseries.

```
bool  InitRealVolume(
   CIndicators*  indicators    // pointer
   )
```

Parameters

indicators

[in]  Pointer to collection of indicators and timeseries.

Return Value

true - successful, otherwise - false.

Note

The RealVolume timeseries is initialized only if Expert Advisor uses the symbol/timeframe different from the symbol/timeframe defined at the first initialization (and timeseries is used further).