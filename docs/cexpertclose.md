Close



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / Close

[![Previous](previous.png)](cexpertcloseall.md) 
[![Next](next.png)](cexpertcloselong.md)

Close

Closes the opened position.

```
virtual bool  Close()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

Closes the position (PositionClose() method of CTrade class object).

Implementation

```
//+------------------------------------------------------------------+
//| Position close                                                   |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation processed, false otherwise.      |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::Close()
  {
   return(m_trade.PositionClose(m_symbol.Name()));
  }
```