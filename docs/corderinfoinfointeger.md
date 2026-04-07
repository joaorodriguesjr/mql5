InfoInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / InfoInteger

[![Previous](previous.png)](corderinfocomment.md) 
[![Next](next.png)](corderinfoinfodouble.md)

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

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.