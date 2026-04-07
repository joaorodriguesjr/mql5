VolumeCurrent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / VolumeCurrent

[![Previous](previous.png)](corderinfovolumeinitial.md) 
[![Next](next.png)](corderinfopriceopen.md)

VolumeCurrent

Gets the unfilled volume of order.

```
double  VolumeCurrent() const
```

Return Value

Unfilled volume of order.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.