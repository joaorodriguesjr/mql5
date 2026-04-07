LotsLimit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CSymbolInfo](csymbolinfo.md) / LotsLimit

[![Previous](previous.png)](csymbolinfolotsstep.md) 
[![Next](next.png)](csymbolinfoswaplong.md)

LotsLimit

Gets the maximal allowed volume of opened position and pending orders (direction insensitive) for one symbol.

```
double  LotsLimit() const
```

Return Value

The maximal allowed volume of opened position and pending orders (direction insensitive) for one symbol.

Note

The symbol should be selected by [Name](csymbolinfoname.md) method.