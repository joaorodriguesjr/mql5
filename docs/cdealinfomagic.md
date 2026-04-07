Magic



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Magic

[![Previous](previous.png)](cdealinfoentrydescription.md) 
[![Next](next.png)](cdealinfopositionid.md)

Magic

Gets the ID of the Expert Advisor, that executed the deal.

```
long  Magic() const
```

Return Value

ID of the Expert Advisor, that executed the deal.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.