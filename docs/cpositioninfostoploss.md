StopLoss



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / StopLoss

[![Previous](previous.png)](cpositioninfopriceopen.md) 
[![Next](next.png)](cpositioninfotakeprofit.md)

StopLoss

Gets the Stop Loss price of the position.

```
double  StopLoss() const
```

Return Value

The Stop Loss price of the position.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.