Symbol



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Symbol

[![Previous](previous.png)](cdealinfoprofit.md) 
[![Next](next.png)](cdealinfocomment.md)

Symbol

Gets the name of the deal symbol.

```
string  Symbol() const
```

Return Value

Name of the deal symbol.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.