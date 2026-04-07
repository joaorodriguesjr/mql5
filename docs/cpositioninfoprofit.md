Profit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / Profit

[![Previous](previous.png)](cpositioninfoswap.md) 
[![Next](next.png)](cpositioninfosymbol.md)

Profit

Gets the amount of current profit of the position.

```
double  Profit() const
```

Return Value

Amount of current profit of the position (in deposit currency).

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.