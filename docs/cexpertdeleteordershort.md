DeleteOrderShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / DeleteOrderShort

[![Previous](previous.png)](cexpertdeleteorderlong.md) 
[![Next](next.png)](cexpertlotopenlong.md)

DeleteOrderShort

Deletes the Sell Limit/Stop order.

```
virtual bool  DeleteOrderShort()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

It deletes the Sell Limit/Stop order (OrderDelete(...) method of CTrade class object).

Implementation

```
//+------------------------------------------------------------------+
//| Delete short limit/stop order                                    |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation successful, false otherwise.     |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::DeleteOrderShort()
  {
   return(m_trade.OrderDelete(m_order.Ticket()));
  }
```