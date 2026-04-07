TypeFillingDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / TypeFillingDescription

[![Previous](previous.png)](corderinfotypefilling.md) 
[![Next](next.png)](corderinfotypetime.md)

TypeFillingDescription

Gets the order filling type as a string.

```
string  TypeFillingDescription() const
```

Return Value

Order filling type as a string.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.