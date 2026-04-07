Magic



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / Magic

[![Previous](previous.png)](chistoryorderinfotypetimedescription.md) 
[![Next](next.png)](chistoryorderinfopositionid.md)

Magic

Gets the ID of the Expert Advisor, that placed the order.

```
long  Magic() const
```

Return Value

ID of the Expert Advisor, that placed the order.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.