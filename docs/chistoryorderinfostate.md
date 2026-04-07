State



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / State

[![Previous](previous.png)](chistoryorderinfotypedescription.md) 
[![Next](next.png)](chistoryorderinfostatedescription.md)

State

Gets the order state.

```
ENUM_ORDER_STATE  State() const
```

Return Value

Order state from [ENUM\_ORDER\_STATE](orderproperties.md#enum_order_state) enumeration.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.