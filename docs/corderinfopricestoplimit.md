PriceStopLimit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / PriceStopLimit

[![Previous](previous.png)](corderinfopricecurrent.md) 
[![Next](next.png)](corderinfosymbol.md)

PriceStopLimit

Gets the price of a pending order.

```
double  PriceStopLimit() const
```

Return Value

Pending order price.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.