DeleteOrder



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / DeleteOrder

[![Previous](previous.png)](cexpertdeleteorders.md) 
[![Next](next.png)](cexpertdeleteorderlong.md)

DeleteOrder

Deletes the Limit/Stop order.

```
virtual bool  DeleteOrder()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

It deletes the Limit/Stop order (OrderDelete(...) method of CTrade class object).

Implementation

```
//+------------------------------------------------------------------+
//| Delete limit/stop order                                          |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation successful, false otherwise.     |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::DeleteOrder()
  {
   return(m_trade.OrderDelete(m_order.Ticket()));
  }
```