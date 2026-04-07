CheckCloseLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / CheckCloseLong

[![Previous](previous.png)](cexpertcheckclose.md) 
[![Next](next.png)](cexpertcheckcloseshort.md)

CheckCloseLong

Checks conditions to close a long position.

```
virtual bool  CheckCloseLong()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

It checks conditions to close a long position (CheckCloseLong() method of Signal object) and if they are satisfied, it closes the open position ([CloseLong(...)](cexpertcloselong.md) method).

Implementation

```
//+------------------------------------------------------------------+
//| Check for long position close or limit/stop order delete         |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation processed, false otherwise.      |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::CheckCloseLong()
  {
   double price=EMPTY_VALUE;
//--- check for long close operations
   if(m_signal.CheckCloseLong(price))
      return(CloseLong(price));
//--- return without operations
   return(false);
  }
```