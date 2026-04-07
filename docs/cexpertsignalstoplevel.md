StopLevel



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / StopLevel

[![Previous](previous.png)](cexpertsignalpricelevel.md) 
[![Next](next.png)](cexpertsignaltakelevel.md)

StopLevel

Sets new value of "StopLevel" parameter.

```
void  StopLevel(
   double    value         // value
   )
```

Parameters

value

[in]  New value of "StopLevel".

Return Value

None.

Note

The value of "StopLevel" is defined in price level units. The numerical values of price level unit is returned by PriceLevelUnit() method. The "StopLevel" is used to define the Stop Loss price relative to the open price.