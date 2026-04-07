CheckTrailingStopLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / CheckTrailingStopLong

[![Previous](previous.png)](cexpertchecktrailingstop.md) 
[![Next](next.png)](cexpertchecktrailingstopshort.md)

CheckTrailingStopLong

It checks Trailing Stop conditions of the opened long position.

```
virtual bool  CheckTrailingStopLong()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

It checks Trailing Stop conditions of the opened long position (CheckTrailingStopLong(...) method of Expert Trailing object). If conditions are satisfied, it modifies the position parameters ([TrailingStopLong(...)](cexperttrailingstoplong.md) method).

Implementation

```
//+------------------------------------------------------------------+
//| Check for trailing stop/profit long position                     |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation processed, false otherwise.      |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::CheckTrailingStopLong()
  {
   double sl=EMPTY_VALUE;
   double tp=EMPTY_VALUE;
//--- check for long trailing stop operations
   if(m_trailing.CheckTrailingStopLong(GetPointer(m_position),sl,tp))
     {
      if(sl==EMPTY_VALUE) sl=m_position.StopLoss();
      if(tp==EMPTY_VALUE) tp=m_position.TakeProfit();
      //--- long trailing stop operations
      return(TrailingStopLong(sl,tp));
     }
//--- return without operations
   return(false);
  }
```