TakeProfit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TakeProfit

[![Previous](previous.png)](corderinfostoploss.md) 
[![Next](next.png)](corderinfopricecurrent.md)

TakeProfit

Gets the order's Take Profit.

```
double  TakeProfit() const
```

Return Value

Order's Take Profit.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.