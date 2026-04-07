StopLoss



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / StopLoss

[![Previous](previous.png)](chistoryorderinfopriceopen.md) 
[![Next](next.png)](chistoryorderinfotakeprofit.md)

StopLoss

Gets the Stop Loss price of the order.

```
double  StopLoss() const
```

Return Value

Stop Loss price of the order.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.