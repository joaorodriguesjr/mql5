Open



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / Open

[![Previous](previous.png)](cchartnextchart.md) 
[![Next](next.png)](cchartdetach.md)

Open

Opens chart with specified parameters and assigns it to the class instance.

```
long  Open(
   const string     symbol_name,     // symbol
   ENUM_TIMEFRAMES  timeframe        // period
   )
```

Parameters

symbol\_name

[in]  Chart symbol. [NULL](void.md) means the symbol of the current chart (to which an expert is attached).

timeframe

[in]  Chart timeframe (from [ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration). 0 means the current timeframe.

Return Value

chart identifier.