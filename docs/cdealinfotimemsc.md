Time



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / TimeMsc

[![Previous](previous.png)](cdealinfotime.md) 
[![Next](next.png)](cdealinfodealtype.md)

TimeMsc

Receives the time of a deal execution in milliseconds since 01.01.1970.

```
ulong  TimeMsc() const
```

Return Value

The time of a deal execution in milliseconds since 01.01.1970.

Note

Deal should be preliminarily selected for access using [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) method.