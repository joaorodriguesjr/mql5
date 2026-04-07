InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CSymbolInfo](csymbolinfo.md) / InfoString

[![Previous](previous.png)](csymbolinfoinfodouble.md) 
[![Next](next.png)](csymbolinfonormalizeprice.md)

InfoString

Gets the value of specified string type property.

```
bool  InfoString(
   ENUM_SYMBOL_INFO_STRING  prop_id,     // property ID
   string&                  var          // reference to variable
   ) const
```

Parameters

prop\_id

[in]  ID of text property.

var

[out]  Reference to [string](stringconst.md) type variable to place result.

Return Value

true success, false unable to get property value.

Note

The symbol should be selected by [Name](csymbolinfoname.md) method.