TakeProfit



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / TakeProfit

[![Previous](previous.png)](chistoryorderinfostoploss.md) 
[![Next](next.png)](chistoryorderinfopricecurrent.md)

TakeProfit

Gets the Take Profit price of the order.

```
double  TakeProfit() const
```

Return Value

The Take Profit price of the order.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.