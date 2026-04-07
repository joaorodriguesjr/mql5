InitLow



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / InitLow

[![Previous](previous.png)](cexpertbaseinithigh.md) 
[![Next](next.png)](cexpertbaseinitclose.md)

InitLow

Initalizes the Low timeseries.

```
bool  InitLow(
   CIndicators*  indicators    // pointer
   )
```

Parameters

indicators

[in]  Pointer to collection of indicators and timeseries.

Return Value

true - successful, otherwise - false.

Note

The Low timeseries is initialized only if the object uses the symbol/timeframe different from the symbol/timeframe defined at the first initialization (and timeseries is used further).