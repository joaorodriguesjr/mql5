Magic



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / Magic

[![Previous](previous.png)](cpositioninfotypedescription.md) 
[![Next](next.png)](cpositioninfoidentifier.md)

Magic

Gets the ID of Expert Advisor that opened the position.

```
long  Magic() const
```

Return Value

ID of the Expert Advisor that opened the position.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.