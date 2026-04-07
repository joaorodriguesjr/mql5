Time



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Time

[![Previous](previous.png)](cdealinfoorder.md) 
[![Next](next.png)](cdealinfotimemsc.md)

Time

Gets the time of deal execution.

```
datetime  Time() const
```

Return Value

Time of deal execution.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.