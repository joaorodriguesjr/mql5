TypeTimeDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TypeTimeDescription

[![Previous](previous.png)](chistoryorderinfotypetime.md) 
[![Next](next.png)](chistoryorderinfomagic.md)

TypeTimeDescription

Gets the order type by expiration time as a string.

```
string  TypeTimeDescription() const
```

Return Value

Order type by expiration time as a string.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.