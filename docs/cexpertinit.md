Init



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / Init

[![Previous](previous.png)](cexpert.md) 
[![Next](next.png)](cexpertmagic.md)

Init

Class instance initialization method.

```
bool  Init(
   string             symbol,        // symbol
   ENUM_TIMEFRAMES    period,        // timeframe
   bool               every_tick,    // flag
   ulong              magic          // Expert Advisor identifier
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe from [ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration.

every\_tick

[in]  Flag.

magic

[in]  Expert Advisor ID (Magic number).

Return Value

None.

Note

If every\_tick is set to true, the [Processing()](cexpertprocessing.md) method is called at each tick of the working symbol. otherwise, the [Processing()](cexpertprocessing.md) is called only when a new bar is formed on the working timeframe of the EA's working symbol.