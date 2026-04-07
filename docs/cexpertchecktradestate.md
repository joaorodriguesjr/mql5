CheckTradeState



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / CheckTradeState

[![Previous](previous.png)](cexperthistorypoint.md) 
[![Next](next.png)](cexpertwaitevent.md)

CheckTradeState

Compares the current state with the saved one and calls the corresponding event handler.

```
bool  CheckTradeState()
```

Return Value

true - event has been handled, otherwise - false.

Note

It checks the number of positions, orders, deals, and historical orders by comparing with the values saved by [HistoryPoint()](cexperthistorypoint.md) method. If trade history has changed, it calls the corresponding virtual event handler.