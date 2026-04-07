TypeDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / TypeDescription

[![Previous](previous.png)](cpositioninfopositiontype.md) 
[![Next](next.png)](cpositioninfomagic.md)

TypeDescription

Gets the position type as a string.

```
string  TypeDescription() const
```

Return Value

Position type as a string.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.