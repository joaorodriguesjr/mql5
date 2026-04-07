PriceCurrent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / PriceCurrent

[![Previous](previous.png)](chistoryorderinfotakeprofit.md) 
[![Next](next.png)](chistoryorderinfopricestoplimi.md)

PriceCurrent

Gets the current price of the order's symbol.

```
double  PriceCurrent() const
```

Return Value

The current price of order's symbol.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.