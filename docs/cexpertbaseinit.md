Init



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / Init

[![Previous](previous.png)](cexpertbaserealvolume.md) 
[![Next](next.png)](cexpertbasesymbol.md)

Init

Initializes the object.

```
bool  Init(
   CSymbolInfo      symbol,   // symbol
   ENUM_TIMEFRAMES  period,   // timeframe
   double           point     // point
   )
```

Parameters

symbol

[in]  Pointer to the object of [CSymbolInfo](csymbolinfo.md) type for access to symbol information.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration).

point

[in]  The "weight" of 2/4-digit point.

Return Value

true - successful completion, otherwise - false.