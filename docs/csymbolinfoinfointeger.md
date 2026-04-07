InfoInteger



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CSymbolInfo](csymbolinfo.md) / InfoInteger

[![Previous](previous.png)](csymbolinfosessionpricelimitmax.md) 
[![Next](next.png)](csymbolinfoinfodouble.md)

InfoInteger

Gets the value of specified integer type property.

```
bool  InfoInteger(
   ENUM_SYMBOL_INFO_INTEGER  prop_id,     // property ID
   long&                     var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of integer type property from [ENUM\_SYMBOL\_INFO\_INTEGER](marketinfoconstants.md#enum_symbol_info_integer) enumeration.

var

[out]  Reference to [long](integertypes.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The symbol should be selected by [Name](csymbolinfoname.md) method.