Commision



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Commision

[![Previous](previous.png)](cdealinfoprice.md) 
[![Next](next.png)](cdealinfoswap.md)

Commission

Gets the amount of commission of the deal.

```
double  Commission() const
```

Return Value

Amount of commission of the deal.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.