CheckClose



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / CheckClose

[![Previous](previous.png)](cexpertreverseshort.md) 
[![Next](next.png)](cexpertcheckcloselong.md)

CheckClose

Checks conditions to close position.

```
virtual bool  CheckClose()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

1. It checks Expert Advisor Stop Out conditions (CheckClose() method of money management object). If condition is satisfied, it closes the position, deletes all orders ([CloseAll()](cexpertcloseall.md)), and exits.
2. It checks conditions to close long or short position ([CheckCloseLong()](cexpertcheckcloselong.md) or [CheckCloseShort()](cexpertcheckcloseshort.md) methods) and if position is closed, it deletes all orders ([DeleteOrders()](cexpertdeleteorders.md) method).

Implementation

```
//+------------------------------------------------------------------+
//| Check for position close or limit/stop order delete              |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation processed, false otherwise.      |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::CheckClose()
  {
   double lot;
//--- position must be selected before call
   if((lot=m_money.CheckClose(GetPointer(m_position)))!=0.0)
      return(CloseAll(lot));
//--- check for position type
   if(m_position.PositionType()==POSITION_TYPE_BUY)
     {
      //--- check the possibility of closing the long position / delete pending orders to buy
      if(CheckCloseLong())
        {
         DeleteOrders();
         return(true);
        }
     }
   else
     {
      //--- check the possibility of closing the short position / delete pending orders to sell
      if(CheckCloseShort())
        {
         DeleteOrders();
         return(true);
        }
     }
//--- return without operations
   return(false);
  }
```