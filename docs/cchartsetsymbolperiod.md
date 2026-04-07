SetSymbolPeriod



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / SetSymbolPeriod

[![Previous](previous.png)](cchartsetstring.md) 
[![Next](next.png)](cchartapplytemplate.md)

SetSymbolPeriod

Changes symbol and period of the chart assigned to the class instance.

```
bool  SetSymbolPeriod(
   const string     symbol_name,     // symbol
   ENUM_TIMEFRAMES  timeframe        // period
   )
```

Parameters

symbol\_name

[in]  New chart symbol. [NULL](void.md) means the symbol of the current chart (to which an expert is attached).

timeframe

[in]  New chart timeframe (from [ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration). 0 means the current chart timeframe.

Return Value

true - successful, false - cannot change the property.