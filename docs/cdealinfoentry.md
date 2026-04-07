Entry



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / Entry

[![Previous](previous.png)](cdealinfotypedescription.md) 
[![Next](next.png)](cdealinfoentrydescription.md)

Entry

Compares the deal direction.

```
ENUM_DEAL_ENTRY  Entry() const
```

Return Value

Deal direction (value of [ENUM\_DEAL\_ENTRY](dealproperties.md#enum_deal_entry) enumeration).

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.