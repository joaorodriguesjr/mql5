PositionType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / PositionType

[![Previous](previous.png)](cpositioninfotimeupdatemsc.md) 
[![Next](next.png)](cpositioninfotypedescription.md)

PositionType

Gets the position type.

```
ENUM_POSITION_TYPE  PositionType() const
```

Return Value

Position type from [ENUM\_POSITION\_TYPE](positionproperties.md#enum_position_type) enumeration.

Note

The position should be selected using the [Select](cpositioninfoselect.md) (by ticket) or [SelectByIndex](cpositioninfoselectbyindex.md) (by index) methods.