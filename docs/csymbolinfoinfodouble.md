InfoDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CSymbolInfo](csymbolinfo.md) / InfoDouble

[![Previous](previous.png)](csymbolinfoinfointeger.md) 
[![Next](next.png)](csymbolinfoinfostring.md)

InfoDouble

Gets the value of specified double type property.

```
bool  InfoDouble(
   ENUM_SYMBOL_INFO_DOUBLE  prop_id,     // property ID
   double&                  var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of double type property from [ENUM\_SYMBOL\_INFO\_DOUBLE](marketinfoconstants.md#enum_symbol_info_double) enumeration.

var

[out]  Reference to [double](double.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The symbol should be selected by [Name](csymbolinfoname.md) method.