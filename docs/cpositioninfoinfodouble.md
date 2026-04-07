InfoDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / InfoDouble

[![Previous](previous.png)](cpositioninfoinfointeger.md) 
[![Next](next.png)](cpositioninfoinfostring.md)

InfoDouble

Gets the value of specified double type property.

```
bool  InfoDouble(
   ENUM_POSITION_PROPERTY_DOUBLE  prop_id,     // property ID
   double&                        var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of double type property from [ENUM\_POSITION\_PROPERTY\_DOUBLE](positionproperties.md#enum_position_property_double) enumeration.

var

[in]  Reference to [double](double.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.