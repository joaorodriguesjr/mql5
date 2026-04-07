OnChartEventProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / OnChartEventProcess

[![Previous](previous.png)](cexpertontimerprocess.md) 
[![Next](next.png)](cexpertonbookeventprocess.md)

OnChartEventProcess

Sets a flag to handle the [OnChartEvent](onchartevent.md) event.

```
void  OnChartEventProcess(
   bool     value        // flag
   )
```

Parameters

value

[in] Flag to handle the [OnChartEvent](onchartevent.md) event.

Return Value

None.

Note

If the flag is true, the [OnChartEvent](onchartevent.md) event is handled. By default, the flag is set to false.