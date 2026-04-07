Symbol



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / Symbol

[![Previous](previous.png)](chistoryorderinfopricestoplimi.md) 
[![Next](next.png)](chistoryorderinfocomment.md)

Symbol

Gets the name of order symbol.

```
string  Symbol() const
```

Return Value

Name of order symbol.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.