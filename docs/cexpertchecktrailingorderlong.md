CheckTrailingOrderLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / CheckTrailingOrderLong

[![Previous](previous.png)](cexperttrailingstopshort.md) 
[![Next](next.png)](cexpertchecktrailingordershort.md)

CheckTrailingOrderLong

Checks Trailing Stop conditions of Buy Limit/Stop trailing order.

```
virtual bool  CheckTrailingOrderLong()
```

Return Value

true - trade operation has been executed, otherwise - false.

Note

It checks Trailing Stop conditions for buy limit/stop trailing order (CheckTrailingOrderLong() method of Trade Signals object) and modifies the order parameters if necessary ([TrailingOrderLong(...)](cexperttrailingorderlong.md) method).

Implementation

```
//+------------------------------------------------------------------+
//| Check for trailing long limit/stop order                         |
//| INPUT:  no.                                                      |
//| OUTPUT: true-if trade operation processed, false otherwise.      |
//| REMARK: no.                                                      |
//+------------------------------------------------------------------+
bool CExpert::CheckTrailingOrderLong()
  {
   double price;
//--- check the possibility of modifying the long order
   if(m_signal.CheckTrailingOrderLong(GetPointer(m_order),price))
      return(TrailingOrderLong(m_order.PriceOpen()-price));
//--- return without operations
   return(false);
  }
```