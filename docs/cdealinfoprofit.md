Profit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Profit

[![Previous](previous.png)](cdealinfoswap.md) 
[![Next](next.png)](cdealinfosymbol.md)

Profit

Gets the financial result of the deal.

```
double  Profit() const
```

Return Value

Financial result of the deal (in deposit currency).

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.