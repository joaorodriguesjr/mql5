PriceOpen



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / PriceOpen

[![Previous](previous.png)](corderinfovolumecurrent.md) 
[![Next](next.png)](corderinfostoploss.md)

PriceOpen

Gets the order price.

```
double  PriceOpen() const
```

Return Value

Price of order placement.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.