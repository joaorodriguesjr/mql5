TimeDone



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TimeDone

[![Previous](previous.png)](chistoryorderinfotimeexpiration.md) 
[![Next](next.png)](chistoryorderinfotimedonemsc.md)

TimeDone

Gets the time of order execution or cancellation.

```
datetime  TimeDone() const
```

Return Value

Time of order execution or cancellation.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.