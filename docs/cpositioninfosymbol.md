Symbol



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / Symbol

[![Previous](previous.png)](cpositioninfoprofit.md) 
[![Next](next.png)](cpositioninfocomment.md)

Symbol

Gets the name of position symbol.

```
string  Symbol() const
```

Return Value

Name of position symbol.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.