Swap



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / Swap

[![Previous](previous.png)](cpositioninfocommission.md) 
[![Next](next.png)](cpositioninfoprofit.md)

Swap

Gets the amount of swap of the position.

```
double  Swap() const
```

Return Value

Amount of swap of the position (in deposit currency).

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.