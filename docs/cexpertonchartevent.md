OnChartEvent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / OnChartEvent

[![Previous](previous.png)](cexpertontimer.md) 
[![Next](next.png)](cexpertonbookevent.md)

OnChartEvent

[OnChartEvent](onchartevent.md) event handler.

```
virtual void  OnChartEvent(
   const int     id,       // event id
   const long&   lparam,   // long type event parameter
   const double  dparam,   // double type event parameter
   const string  sparam    // string type event parameter
   )
```

Parameters

id

[in]  Event ID.

lparam

[in] Event parameter of long type.

dparam

[in]  Event parameter of double type.

sparam

[in]  Event parameter of string type.

Return Value

None.