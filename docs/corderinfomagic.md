Magic



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / Magic

[![Previous](previous.png)](corderinfotypetimedescription.md) 
[![Next](next.png)](corderinfopositionid.md)

Magic

Gets the ID of an Expert Advisor that placed the order.

```
long  Magic() const
```

Return Value

ID of an Expert Advisor that placed the order.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.