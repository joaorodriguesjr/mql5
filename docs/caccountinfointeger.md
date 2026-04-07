Integer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CAccountInfo](caccountinfo.md) / InfoInteger

[![Previous](previous.png)](caccountinfocompany.md) 
[![Next](next.png)](caccountinfodouble.md)

InfoInteger

Gets the value of specified integer type property.

```
long  InfoInteger(
   ENUM_ACCOUNT_INFO_INTEGER  prop_id     // property ID
   ) const
```

Parameters

prop\_id

[in]  Identifier of the property. The value can be one of the values of [ENUM\_ACCOUNT\_INFO\_INTEGER](accountinformation.md#enum_account_info_integer) enumeration.

Return Value

Value of [long](integertypes.md) type.