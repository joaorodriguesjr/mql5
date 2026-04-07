Swap



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Swap

[![Previous](previous.png)](cdealinfocommision.md) 
[![Next](next.png)](cdealinfoprofit.md)

Swap

Gets the amount of swap when position is closed.

```
double  Swap() const
```

Return Value

Amount of swap when position is closed.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.