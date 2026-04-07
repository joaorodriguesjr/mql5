InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / InfoString

[![Previous](previous.png)](chistoryorderinfoinfodouble.md) 
[![Next](next.png)](chistoryorderinfoticket.md)

InfoString

Gets the value of specified string type property.

```
bool  InfoString(
   ENUM_ORDER_PROPERTY_STRING  prop_id,     // property ID
   string&                     var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of text property from [ENUM\_ORDER\_PROPERTY\_STRING](orderproperties.md#enum_order_property_string) enumeration.

var

[out]  Reference to [string](stringconst.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.