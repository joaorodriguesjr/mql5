InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / InfoString

[![Previous](previous.png)](cdealinfoinfodouble.md) 
[![Next](next.png)](cdealinfoticket.md)

InfoString

Gets the value of specified string type property.

```
bool  InfoString(
   ENUM_DEAL_PROPERTY_STRING  prop_id,     // property ID
   string&                    var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of text property from [ENUM\_DEAL\_PROPERTY\_STRING](dealproperties.md#enum_deal_property_string) enumeration.

var

[out]  Reference to [string](stringconst.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.