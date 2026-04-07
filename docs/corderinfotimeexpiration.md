TimeExpiration



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TimeExpiration

[![Previous](previous.png)](corderinfostatedescription.md) 
[![Next](next.png)](corderinfotimedone.md)

TimeExpiration

Gets the order expiration time.

```
datetime  TimeExpiration() const
```

Return Value

Order expiration time, set on its placement.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.