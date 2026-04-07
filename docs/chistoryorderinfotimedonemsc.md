TimeDone



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TimeDoneMsc

[![Previous](previous.png)](chistoryorderinfotimedone.md) 
[![Next](next.png)](chistoryorderinfotypefilling.md)

TimeDoneMsc

Receives order execution or cancellation time in milliseconds since 01.01.1970.

```
ulong  TimeDoneMsc() const
```

Return Value

Order execution or cancellation time in milliseconds since 01.01.1970.

Note

Historical order should be preliminarily selected for access using [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) method.