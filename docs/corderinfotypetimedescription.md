TypeTimeDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TypeTimeDescription

[![Previous](previous.png)](corderinfotypetime.md) 
[![Next](next.png)](corderinfomagic.md)

TypeTimeDescription

Gets the order type by expiration time as a string.

```
string  TypeTimeDescription() const
```

Return Value

Order type by expiration time as a string.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.