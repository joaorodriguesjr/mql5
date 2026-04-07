CheckOpen



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / CheckOpen

[![Previous](previous.png)](cexpertselectposition.md) 
[![Next](next.png)](cexpertcheckopenlong.md)

CheckOpen

Checks conditions to open a position.

```
virtual bool  CheckOpen()
```

Return Value

true - a trade operation has been executed, otherwise - false.

Note

It checks the necessity to open long ([CheckOpenLong()](cexpertcheckopenlong.md)) and short ([CheckOpenShort()](cexpertcheckopenshort.md)) positions.

Implementation

```
//+------------------------------------------------------------------+
//| Check for position open or limit/stop order set                  |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation processed, false otherwise.      |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::CheckOpen()
  {
   if(CheckOpenLong())  return(true);
   if(CheckOpenShort()) return(true);
//--- return without operations
   return(false);
  }
```