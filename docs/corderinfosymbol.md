Symbol



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / Symbol

[![Previous](previous.png)](corderinfopricestoplimit.md) 
[![Next](next.png)](corderinfocomment.md)

Symbol

Gets the name of order symbol.

```
string  Symbol() const
```

Return Value

Name of order symbol.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.