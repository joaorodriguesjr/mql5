InfoDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / InfoDouble

[![Previous](previous.png)](corderinfoinfointeger.md) 
[![Next](next.png)](corderinfoinfostring.md)

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

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.