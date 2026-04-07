InfoInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / InfoInteger

[![Previous](previous.png)](cdealinfocomment.md) 
[![Next](next.png)](cdealinfoinfodouble.md)

InfoInteger

Gets the value of specified integer type property.

```
bool  InfoInteger(
   ENUM_DEAL_PROPERTY_INTEGER  prop_id,     // property ID
   long&                       var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of integer type property from [ENUM\_DEAL\_PROPERTY\_INTEGER](dealproperties.md#enum_deal_property_integer) enumeration.

var

[out]  Reference to [long](integertypes.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.