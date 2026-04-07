Period



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / Period

[![Previous](previous.png)](cexpertbasesymbol.md) 
[![Next](next.png)](cexpertbasemagic.md)

Period

Sets the object timeframe.

```
bool  Period(
   ENUM_TIMEFRAMES  value     // timeframe
   )
```

Parameters

value

[in]  Timeframe.

Return Value

true - successful, otherwise - false.

Note

The setting of working timeframe is necessary if the object uses the timeframe different from timeframe defined at the initialization.