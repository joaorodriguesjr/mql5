PositionId



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / PositionId

[![Previous](previous.png)](chistoryorderinfomagic.md) 
[![Next](next.png)](chistoryorderinfovolumeinitial.md)

PositionId

Gets the ID of position.

```
long  PositionId() const
```

Return Value

ID of position, in which the order was involved.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.