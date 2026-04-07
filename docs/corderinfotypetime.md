TypeTime



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TypeTime

[![Previous](previous.png)](corderinfotypefillingdescription.md) 
[![Next](next.png)](corderinfotypetimedescription.md)

TypeTime

Gets the type of order at the time of the expiration.

```
ENUM_ORDER_TYPE_TIME  TypeTime() const
```

Return Value

Type of order at the time of the expiration from [ENUM\_ORDER\_TYPE\_TIME](orderproperties.md) enumeration.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.