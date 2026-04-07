PriceCurrent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / PriceCurrent

[![Previous](previous.png)](corderinfotakeprofit.md) 
[![Next](next.png)](corderinfopricestoplimit.md)

PriceCurrent

Gets the current price by order symbol.

```
double  PriceCurrent() const
```

Return Value

Current price by order symbol.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.