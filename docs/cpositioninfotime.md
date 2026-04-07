Time



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / Time

[![Previous](previous.png)](cpositioninfo.md) 
[![Next](next.png)](cpositioninfotimemsc.md)

Time

Gets the time of position opening.

```
datetime  Time() const
```

Return Value

Time of position opening.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.