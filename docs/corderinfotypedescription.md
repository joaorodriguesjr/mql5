TypeDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TypeDescription

[![Previous](previous.png)](corderinfoordertype.md) 
[![Next](next.png)](corderinfostate.md)

TypeDescription

Gets the order type as a string.

```
string  TypeDescription() const
```

Return Value

Order type as a string.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.