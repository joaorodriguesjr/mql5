Ticket



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / Ticket

[![Previous](previous.png)](corderinfo.md) 
[![Next](next.png)](corderinfotimesetup.md)

Ticket

Gets the ticket of an order.

```
ulong  Ticket() const
```

Return Value

Order ticket if successful, otherwise - [ULONG\_MAX](typeconstants.md).

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.