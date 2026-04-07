OrderType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / OrderType

[![Previous](previous.png)](corderinfotimesetupmsc.md) 
[![Next](next.png)](corderinfotypedescription.md)

OrderType

Gets the order type.

```
ENUM_ORDER_TYPE  OrderType()
```

Return Value

Order type from [ENUM\_ORDER\_TYPE](orderproperties.md#enum_order_type) enumeration.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.