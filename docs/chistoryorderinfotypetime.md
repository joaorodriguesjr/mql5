TypeTime



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TypeTime

[![Previous](previous.png)](chistoryorderinfotypefillingdescription.md) 
[![Next](next.png)](chistoryorderinfotypetimedescription.md)

TypeTime

Gets the type of order at the time of the expiration.

```
ENUM_ORDER_TYPE_TIME  TypeTime() const
```

Return Value

Type of order at the time of the expiration from [ENUM\_ORDER\_TYPE\_TIME](orderproperties.md#enum_order_type_time) enumeration.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.