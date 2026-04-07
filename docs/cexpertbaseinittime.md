InitTime



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / InitTime

[![Previous](previous.png)](cexpertbaseinitspread.md) 
[![Next](next.png)](cexpertbaseinittickvolume.md)

InitTime

Initalizes the Time timeseries.

```
bool  InitTime(
   CIndicators*  indicators    // pointer
   )
```

Parameters

indicators

[in]  Pointer to collection of indicators and timeseries.

Return Value

true - successful, otherwise - false.

Note

The Time timeseries is initialized only if Expert Advisor uses the symbol/timeframe different from the symbol/timeframe defined at the first initialization (and timeseries is used further).