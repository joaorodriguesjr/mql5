StateDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / StateDescription

[![Previous](previous.png)](corderinfostate.md) 
[![Next](next.png)](corderinfotimeexpiration.md)

StateDescription

Gets the order state as a string.

```
string  StateDescription() const
```

Return Value

Order state as a string.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.