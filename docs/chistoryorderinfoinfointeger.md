InfoInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / InfoInteger

[![Previous](previous.png)](chistoryorderinfocomment.md) 
[![Next](next.png)](chistoryorderinfoinfodouble.md)

InfoInteger

Gets the value of specified integer type property.

```
bool  InfoInteger(
   ENUM_ORDER_PROPERTY_INTEGER  prop_id,     // property ID
   long&                        var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of integer type property from [ENUM\_ORDER\_PROPERTY\_INTEGER](orderproperties.md#enum_order_property_integer) enumeration.

var

[out]  Reference to [long](integertypes.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.