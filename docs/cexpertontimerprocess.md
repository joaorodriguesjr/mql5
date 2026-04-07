OnTimerProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / OnTimerProcess

[![Previous](previous.png)](cexpertontradeprocess.md) 
[![Next](next.png)](cexpertoncharteventprocess.md)

OnTimerProcess

Sets the [OnTimer](ontimer.md) event handling flag.

```
void  OnTimerProcess(
   bool     value        // flag
   )
```

Parameters

value

[in] [OnTimer](ontimer.md) event handling flag.

Return Value

None.

Note

If the flag is true, the [OnTimer](ontimer.md) event is handled. By default, the flag is set to false.