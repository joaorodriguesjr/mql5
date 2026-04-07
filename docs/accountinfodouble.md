AccountInfoDouble



[MQL5 Reference](index.md)  /  [Account Information](account.md) / AccountInfoDouble

[![Previous](previous.png)](account.md) 
[![Next](next.png)](accountinfointeger.md)

AccountInfoDouble

Returns the value of the appropriate account property.

```
double  AccountInfoDouble(
   ENUM_ACCOUNT_INFO_DOUBLE  property_id      // Property identifier
   );
```

Parameters

property\_id

[in]  Property identifier. The value can be one of the values of [ENUM\_ACCOUNT\_INFO\_DOUBLE](accountinformation.md#enum_account_info_double).

Return Value

Value of [double](double.md) type.

Example:

```
void OnStart()
  {
//--- Show all the information available from the function AccountInfoDouble()
   printf("ACCOUNT_BALANCE =  %G",AccountInfoDouble(ACCOUNT_BALANCE));
   printf("ACCOUNT_CREDIT =  %G",AccountInfoDouble(ACCOUNT_CREDIT));
   printf("ACCOUNT_PROFIT =  %G",AccountInfoDouble(ACCOUNT_PROFIT));
   printf("ACCOUNT_EQUITY =  %G",AccountInfoDouble(ACCOUNT_EQUITY));
   printf("ACCOUNT_MARGIN =  %G",AccountInfoDouble(ACCOUNT_MARGIN));
   printf("ACCOUNT_MARGIN_FREE =  %G",AccountInfoDouble(ACCOUNT_MARGIN_FREE));
   printf("ACCOUNT_MARGIN_LEVEL =  %G",AccountInfoDouble(ACCOUNT_MARGIN_LEVEL));
   printf("ACCOUNT_MARGIN_SO_CALL = %G",AccountInfoDouble(ACCOUNT_MARGIN_SO_CALL));
   printf("ACCOUNT_MARGIN_SO_SO = %G",AccountInfoDouble(ACCOUNT_MARGIN_SO_SO));
  }
```

See also

[SymbolInfoDouble](symbolinfodouble.md), [SymbolInfoString](symbolinfostring.md), [SymbolInfoInteger](symbolinfointeger.md), [PrintFormat](printformat.md)