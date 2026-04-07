DealType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / DealType

[![Previous](previous.png)](cdealinfotimemsc.md) 
[![Next](next.png)](cdealinfotypedescription.md)

DealType

Gets the deal type.

```
ENUM_DEAL_TYPE  DealType() const
```

Return Value

Deal type from [ENUM\_DEAL\_TYPE](dealproperties.md#enum_deal_type) enumeration.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.