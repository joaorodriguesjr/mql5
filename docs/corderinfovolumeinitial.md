VolumeInitial



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / VolumeInitial

[![Previous](previous.png)](corderinfopositionid.md) 
[![Next](next.png)](corderinfovolumecurrent.md)

VolumeInitial

Gets the initial volume of order.

```
double  VolumeInitial() const
```

Return Value

Initial volume of order.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.