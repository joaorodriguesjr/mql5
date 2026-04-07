Refresh



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / Refresh

[![Previous](previous.png)](cindicatorgetdata.md) 
[![Next](next.png)](cindicatorminimum.md)

Refresh

Updates the indicator data. It is recommended calling the method before using [GetData()](cindicatorgetdata.md).

```
virtual void  Refresh(
   int  flags=OBJ_ALL_PERIODS      // flags
   )
```

Parameters

flags=OBJ\_ALL\_PERIODS

[in]  Timeframe update flags.