TypeFilling



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TypeFilling

[![Previous](previous.png)](chistoryorderinfotimedonemsc.md) 
[![Next](next.png)](chistoryorderinfotypefillingdescription.md)

TypeFilling

Gets the type of order execution by remainder.

```
ENUM_ORDER_TYPE_FILLING  TypeFilling() const
```

Return Value

Type of order execution by remainder from [ENUM\_ORDER\_TYPE\_FILLING](orderproperties.md#enum_order_type_filling) enumeration.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.