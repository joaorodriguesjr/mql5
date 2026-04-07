MarginInitial



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CSymbolInfo](csymbolinfo.md) / MarginInitial

[![Previous](previous.png)](csymbolinfoswaprollover3daysdescription.md) 
[![Next](next.png)](csymbolinfomarginmaintenance.md)

MarginInitial

Gets the value of initial margin.

```
double  MarginInitial()
```

Return Value

Value of initial margin.

Note

It returns the amount of margin (in margin currency of instrument) that is charged from one lot. Used to check client's equity, when they enter the market.

The symbol should be selected by [Name](csymbolinfoname.md) method.