Time



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / TimeUpdateMsc

[![Previous](previous.png)](cpositioninfotimeupdate.md) 
[![Next](next.png)](cpositioninfopositiontype.md)

TimeUpdateMsc

Receives the time of position changing in milliseconds since 01.01.1970.

```
ulong  TimeUpdateMsc() const
```

Return Value

The time of position changing in milliseconds since 01.01.1970.

Note

Position should be preliminarily selected for access using [Select](cpositioninfoselect.md) (by symbol) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) method.