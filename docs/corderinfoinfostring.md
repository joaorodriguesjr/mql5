InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / InfoString

[![Previous](previous.png)](corderinfoinfodouble.md) 
[![Next](next.png)](corderinfostorestate.md)

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

[in]  ID of string property from [ENUM\_ORDER\_PROPERTY\_STRING](orderproperties.md) enumeration.

var

[out]  Reference to [string](stringconst.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The order should be selected using the [Select](corderinfoselect.md) (by ticket) or [SelectByIndex](corderinfoselectbyindex.md) (by index) methods.