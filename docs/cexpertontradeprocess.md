OnTradeProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / OnTradeProcess

[![Previous](previous.png)](cexpertontickprocess.md) 
[![Next](next.png)](cexpertontimerprocess.md)

OnTradeProcess

Sets the [OnTrade](ontrade.md) event handling flag.

```
void  OnTradeProcess(
   bool     value        // flag
   )
```

Parameters

value

[in] [OnTrade](ontrade.md) event handling flag.

Return Value

None.

Note

If the flag is true, the [OnTrade](ontrade.md) event is handled. By default, the flag is set to false.