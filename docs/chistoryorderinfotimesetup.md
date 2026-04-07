TimeSetup



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TimeSetup

[![Previous](previous.png)](chistoryorderinfo.md) 
[![Next](next.png)](chistoryorderinfotimesetupmsc.md)

TimeSetup

Gets the time of order placement.

```
datetime  TimeSetup() const
```

Return Value

Time of order placement.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.