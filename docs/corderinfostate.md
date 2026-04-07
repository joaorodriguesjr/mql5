State



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / State

[![Previous](previous.png)](corderinfotypedescription.md) 
[![Next](next.png)](corderinfostatedescription.md)

State

Gets the order state.

```
ENUM_ORDER_STATE  State() const
```

Return Value

Order state from [ENUM\_ORDER\_STATE](orderproperties.md#enum_order_state) enumeration.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.