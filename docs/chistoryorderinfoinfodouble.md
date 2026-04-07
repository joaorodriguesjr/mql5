InfoDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CHistoryOrderInfo](chistoryorderinfo.md) / InfoDouble

[![Previous](previous.png)](chistoryorderinfoinfointeger.md) 
[![Next](next.png)](chistoryorderinfoinfostring.md)

InfoDouble

Gets the value of specified double type property.

```
bool  InfoDouble(
   ENUM_ORDER_PROPERTY_DOUBLE  prop_id,     // property ID
   double&                     var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of double type property from [ENUM\_ORDER\_PROPERTY\_DOUBLE](orderproperties.md#enum_order_property_double) enumeration.

var

[out]  Reference to [double](double.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The historical order should be selected using the [Ticket](chistoryorderinfoticket.md) (by ticket) or [SelectByIndex](chistoryorderinfoselectbyindex.md) (by index) methods.