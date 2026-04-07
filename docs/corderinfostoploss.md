StopLoss



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / StopLoss

[![Previous](previous.png)](corderinfopriceopen.md) 
[![Next](next.png)](corderinfotakeprofit.md)

StopLoss

Gets the order's Stop Loss.

```
double  StopLoss() const
```

Return Value

Order's Stop Loss.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.