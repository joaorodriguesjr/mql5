PositionId



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / PositionId

[![Previous](previous.png)](cdealinfomagic.md) 
[![Next](next.png)](cdealinfovolume.md)

PositionId

Gets the ID of position, in which the deal was involved.

```
long  PositionId() const
```

Return Value

ID of position, in which the deal was involved.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.