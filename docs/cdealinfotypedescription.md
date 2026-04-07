TypeDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / TypeDescription

[![Previous](previous.png)](cdealinfodealtype.md) 
[![Next](next.png)](cdealinfoentry.md)

TypeDescription

Gets the deal type as a string.

```
string  TypeDescription() const
```

Return Value

Deal type as a string.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.