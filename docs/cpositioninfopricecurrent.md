PriceCurrent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / PriceCurrent

[![Previous](previous.png)](cpositioninfotakeprofit.md) 
[![Next](next.png)](cpositioninfocommission.md)

PriceCurrent

Gets the current price by position symbol.

```
double  PriceCurrent() const
```

Return Value

Current price by position symbol.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.