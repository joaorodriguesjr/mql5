Order



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Order

[![Previous](previous.png)](cdealinfo.md) 
[![Next](next.png)](cdealinfotime.md)

Order

Gets the order by which the deal is executed.

```
long  Order() const
```

Return Value

Order by which the deal is executed.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.