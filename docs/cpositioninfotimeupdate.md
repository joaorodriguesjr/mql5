Time



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / TimeUpdate

[![Previous](previous.png)](cpositioninfotimemsc.md) 
[![Next](next.png)](cpositioninfotimeupdatemsc.md)

TimeUpdate

Receives the time of position changing in seconds since 01.01.1970.

```
datetime  TimeUpdate() const
```

Return Value

Time of position changing in seconds since 01.01.1970.

Note

Position should be preliminarily selected for access using [Select](cpositioninfoselect.md) (by symbol) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) method.