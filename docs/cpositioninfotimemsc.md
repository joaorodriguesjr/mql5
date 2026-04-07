Time



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / TimeMsc

[![Previous](previous.png)](cpositioninfotime.md) 
[![Next](next.png)](cpositioninfotimeupdate.md)

TimeMsc

Receives position opening time in milliseconds since 01.01.1970.

```
ulong  TimeMsc() const
```

Return Value

Position opening time in milliseconds since 01.01.1970.

Note

Position should be preliminarily selected for access using [Select](cpositioninfoselect.md) (by symbol) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) method.