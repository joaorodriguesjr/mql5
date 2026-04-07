InfoDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CDealInfo](cdealinfo.md) / InfoDouble

[![Previous](previous.png)](cdealinfoinfointeger.md) 
[![Next](next.png)](cdealinfoinfostring.md)

InfoDouble

Gets the value of specified double type property.

```
bool  InfoDouble(
   ENUM_DEAL_PROPERTY_DOUBLE  prop_id,     // property ID
   double&                    var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of double type property from [ENUM\_DEAL\_PROPERTY\_DOUBLE](dealproperties.md#enum_deal_property_double) enumeration.

var

[out]  Reference to [double](double.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The deal should be selected using the [Ticket](cdealinfoticket.md) (by ticket) or [SelectByIndex](cdealinfoselectbyindex.md) (by index) methods.