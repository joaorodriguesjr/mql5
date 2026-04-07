Commission



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / Commission

[![Previous](previous.png)](cpositioninfopricecurrent.md) 
[![Next](next.png)](cpositioninfoswap.md)

Commission

Gets the amount of commission of the position.

```
double  Commission() const
```

Return Value

Amount of commission of the position (in deposit currency).

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.