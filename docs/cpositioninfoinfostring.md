InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / InfoString

[![Previous](previous.png)](cpositioninfoinfodouble.md) 
[![Next](next.png)](cpositioninfoselect.md)

InfoString

Gets the value of specified string type property.

```
bool  InfoString(
   ENUM_POSITION_PROPERTY_STRING  prop_id,     // property ID
   string&                        var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of text property from [ENUM\_POSITION\_PROPERTY\_STRING](positionproperties.md#enum_position_property_string) enumeration.

var

[out]  Reference to [string](stringconst.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.