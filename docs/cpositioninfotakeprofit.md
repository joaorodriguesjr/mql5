TakeProfit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / TakeProfit

[![Previous](previous.png)](cpositioninfostoploss.md) 
[![Next](next.png)](cpositioninfopricecurrent.md)

TakeProfit

Gets the Take Profit price of the position.

```
double  TakeProfit() const
```

Return Value

The Take Profit price of the position.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.