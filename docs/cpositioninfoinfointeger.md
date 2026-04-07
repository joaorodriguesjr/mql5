InfoInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / InfoInteger

[![Previous](previous.png)](cpositioninfocomment.md) 
[![Next](next.png)](cpositioninfoinfodouble.md)

InfoInteger

Gets the value of specified integer type property.

```
bool  InfoInteger(
   ENUM_POSITION_PROPERTY_INTEGER  prop_id,     // property ID
   long&                           var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of integer type property from [ENUM\_POSITION\_PROPERTY\_INTEGER](positionproperties.md#enum_position_property_integer) enumeration.

var

[out]  Reference to [long](integertypes.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.