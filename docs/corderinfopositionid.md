PositionId



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / PositionId

[![Previous](previous.png)](corderinfomagic.md) 
[![Next](next.png)](corderinfovolumeinitial.md)

PositionId

Gets the ID of position.

```
long  PositionId() const
```

Return Value

ID of position, in which the order was involved.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.