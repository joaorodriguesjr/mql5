TypeFilling



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TypeFilling

[![Previous](previous.png)](corderinfotimedonemsc.md) 
[![Next](next.png)](corderinfotypefillingdescription.md)

TypeFilling

Gets the order filling type.

```
ENUM_ORDER_TYPE_FILLING  TypeFilling() const
```

Return Value

Order filling type from [ENUM\_ORDER\_TYPE\_FILLING](orderproperties.md#enum_order_type_filling) enumeration.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.