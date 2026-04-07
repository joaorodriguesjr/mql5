PriceStopLimit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / PriceStopLimit

[![Previous](previous.png)](chistoryorderinfopricecurrent.md) 
[![Next](next.png)](chistoryorderinfosymbol.md)

PriceStopLimit

Gets the pending order price.

```
double  PriceStopLimit() const
```

Return Value

Pending orders price.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.