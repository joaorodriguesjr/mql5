TimeDone



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TimeDone

[![Previous](previous.png)](corderinfotimeexpiration.md) 
[![Next](next.png)](corderinfotimedonemsc.md)

TimeDone

Gets the time of order execution or cancellation.

```
datetime  TimeDone() const
```

Return Value

Time of order execution or cancellation.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.