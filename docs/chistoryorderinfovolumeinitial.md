VolumeInitial



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / VolumeInitial

[![Previous](previous.png)](chistoryorderinfopositionid.md) 
[![Next](next.png)](chistoryorderinfovolumecurrent.md)

VolumeInitial

Gets the initial volume of order.

```
double  VolumeInitial() const
```

Return Value

Initial volume of order.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.