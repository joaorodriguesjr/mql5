HistoryPoint



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / HistoryPoint

[![Previous](previous.png)](cexpertpreparehistorydate.md) 
[![Next](next.png)](cexpertchecktradestate.md)

HistoryPoint

Creates a checkpoint of trade history.

```
void  HistoryPoint(
   bool   from_check_trade=false   // flag
   )
```

Parameters

from\_check\_trade=false

[in]  Flag to avoid recursion.

Note

It saves the amount of positions, orders, deals, and historical orders.