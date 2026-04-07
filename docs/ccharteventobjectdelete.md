EventObjectDelete



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / EventObjectDelete

[![Previous](previous.png)](ccharteventobjectcreate.md) 
[![Next](next.png)](cchartindicatoradd.md)

EventObjectDelete

Sets a flag to send notifications of [events](enum_chartevents.md) of a graphical object deletion.

```
bool  EventObjectDelete(
   bool  flag      // flag
   )
```

Parameters

flag

[in]  New value of a flag to send notifications of events of a graphical object deletion.

Return Value

true successful, false - cannot change the flag.