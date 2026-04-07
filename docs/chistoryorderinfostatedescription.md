StateDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / StateDescription

[![Previous](previous.png)](chistoryorderinfostate.md) 
[![Next](next.png)](chistoryorderinfotimeexpiration.md)

StateDescription

Gets the order state as a string.

```
string  StateDescription() const
```

Return Value

Order state as a string.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.