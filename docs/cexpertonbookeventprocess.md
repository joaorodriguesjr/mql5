OnBookEventProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / OnBookEventProcess

[![Previous](previous.png)](cexpertoncharteventprocess.md) 
[![Next](next.png)](cexpertmaxorders.md)

OnBookEventProcess

Sets a flag to handle the [OnBookEvent](onchartevent.md) event.

```
void  OnChartEventProcess(
   bool     value        // flag
   )
```

Parameters

value

[in] Flag to handle the [OnBookEvent](onchartevent.md) event.

Return Value

None.

Note

If the flag is true, the [OnBookEvent](onchartevent.md) event is handled. By default, the flag is set to false.