InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CAccountInfo](caccountinfo.md) / InfoString

[![Previous](previous.png)](caccountinfodouble.md) 
[![Next](next.png)](caccountinfoorderprofitcheck.md)

InfoString

Gets the value of specified string type property.

```
string  InfoString(
   ENUM_ACCOUNT_INFO_STRING  prop_id     // property ID
   ) const
```

Parameters

prop\_id

[in]  Identifier of the property. The value can be one of the values of [ENUM\_ACCOUNT\_INFO\_STRING](accountinformation.md#enum_account_info_string) enumeration.

Return Value

Value of [string](stringconst.md) type.