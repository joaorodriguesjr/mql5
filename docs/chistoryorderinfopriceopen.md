PriceOpen



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / PriceOpen

[![Previous](previous.png)](chistoryorderinfovolumecurrent.md) 
[![Next](next.png)](chistoryorderinfostoploss.md)

PriceOpen

Gets the order price.

```
double  PriceOpen() const
```

Return Value

Price of order placement.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.