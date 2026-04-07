TimeSetup



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TimeSetupMsc

[![Previous](previous.png)](corderinfotimesetup.md) 
[![Next](next.png)](corderinfoordertype.md)

TimeSetupMsc

Receives the time of placing an order for execution in milliseconds since 01.01.1970.

```
ulong  TimeSetupMsc() const
```

Return Value

The time of placing an order for execution in milliseconds since 01.01.1970.

Note

Order should be preliminarily selected for access using [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) method.