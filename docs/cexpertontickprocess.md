OnTickProcess



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / OnTickProcess

[![Previous](previous.png)](cexpertdeinit.md) 
[![Next](next.png)](cexpertontradeprocess.md)

OnTickProcess

Sets the [OnTick](ontick.md) event handling flag.

```
void  OnTickOProcess(
   bool     value        // flag
   )
```

Parameters

value

[in] [OnTick](ontick.md) event handling flag.

Return Value

None.

Note

If the flag is true, the [OnTick](ontick.md) event is handled. By default, the flag is set to true.