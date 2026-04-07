TimeSetup



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TimeSetupMsc

[![Previous](previous.png)](chistoryorderinfotimesetup.md) 
[![Next](next.png)](chistoryorderinfoordertype.md)

TimeSetupMsc

Receives the time of placing an order for execution in milliseconds since 01.01.1970.

```
ulong  TimeSetupMsc() const
```

Return Value

The time of placing an order for execution in milliseconds since 01.01.1970.

Note

Historical order should be preliminarily selected for access using [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) method.