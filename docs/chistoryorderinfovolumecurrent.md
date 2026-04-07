VolumeCurrent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / VolumeCurrent

[![Previous](previous.png)](chistoryorderinfovolumeinitial.md) 
[![Next](next.png)](chistoryorderinfopriceopen.md)

VolumeCurrent

Gets the unfilled volume of order.

```
double  VolumeCurrent() const
```

Return Value

Unfilled volume of order.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.