OrderType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / OrderType

[![Previous](previous.png)](chistoryorderinfotimesetupmsc.md) 
[![Next](next.png)](chistoryorderinfotypedescription.md)

OrderType

Gets the order type.

```
ENUM_ORDER_TYPE  OrderType() const
```

Return Value

Order type from [ENUM\_ORDER\_TYPE](orderproperties.md#enum_order_type) enumeration.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.