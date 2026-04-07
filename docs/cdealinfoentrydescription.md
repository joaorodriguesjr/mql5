EntryDescription



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / EntryDescription

[![Previous](previous.png)](cdealinfoentry.md) 
[![Next](next.png)](cdealinfomagic.md)

EntryDescription

Gets the deal direction as a string.

```
string  EntryDescription() const
```

Return Value

Deal direction as a string.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.