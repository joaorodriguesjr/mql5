TimeExpiration



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TimeExpiration

[![Previous](previous.png)](chistoryorderinfostatedescription.md) 
[![Next](next.png)](chistoryorderinfotimedone.md)

TimeExpiration

Gets the time of order expiration.

```
datetime  TimeExpiration() const
```

Return Value

Time of order expiration, set on its placement.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.