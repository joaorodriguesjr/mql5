DeleteOrders



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / DeleteOrders

[![Previous](previous.png)](cexpertcheckdeleteordershort.md) 
[![Next](next.png)](cexpertdeleteorder.md)

DeleteOrders

Deletes all orders.

```
virtual bool  DeleteOrders()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

It deletes all orders ([DeleteOrder()](cexpertdeleteorder.md) for all orders).

Implementation

```
//+------------------------------------------------------------------+
//| Delete all limit/stop orders                                     |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation successful, false otherwise.     |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::DeleteOrders()
  {
   bool result=false;
   int  total=OrdersTotal();
//---
   for(int i=total-1;i>=0;i--)
     {
      if(m_order.Select(OrderGetTicket(i)))
        {
         if(m_order.Symbol()!=m_symbol.Name()) continue;
         result|=DeleteOrder();
        }
     }
//---
   return(result);
  }
```