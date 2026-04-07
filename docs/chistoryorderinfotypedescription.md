TypeDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TypeDescription

[![Previous](previous.png)](chistoryorderinfoordertype.md) 
[![Next](next.png)](chistoryorderinfostate.md)

TypeDescription

Gets the order type as a string.

```
string  TypeDescription() const
```

Return Value

Order type as a string.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.