TimeSetup



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TimeSetup

[![Previous](previous.png)](corderinfoticket.md) 
[![Next](next.png)](corderinfotimesetupmsc.md)

TimeSetup

Gets the time of order placement.

```
datetime  TimeSetup() const
```

Return Value

Time of order placement.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.