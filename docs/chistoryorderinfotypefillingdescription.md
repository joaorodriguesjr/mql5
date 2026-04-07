TypeFillingDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TypeFillingDescription

[![Previous](previous.png)](chistoryorderinfotypefilling.md) 
[![Next](next.png)](chistoryorderinfotypetime.md)

TypeFillingDescription

Gets the type of order execution by remainder as a string.

```
string  TypeFillingDescription() const
```

Return Value

Type order of execution by remainder as a string.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.