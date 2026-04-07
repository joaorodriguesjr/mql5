MaxLotCheck



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CAccountInfo](caccountinfo.md) / MaxLotCheck

[![Previous](previous.png)](caccountinfofreemargincheck.md) 
[![Next](next.png)](csymbolinfo.md)

MaxLotCheck

Gets the maximum possible volume of trade operation.

```
double  MaxLotCheck(
   const string        symbol,              // symbol
   ENUM_ORDER_TYPE     trade_operation,     // order type (ORDER_TYPE_BUY or ORDER_TYPE_SELL)
   double              price,               // price
   double              percent=100          // percent of available margin (default is 100%)
   ) const
```

Parameters

symbol

[in]  Symbol for trade operation.

trade\_operation

[in]  Type of trade operation from [ENUM\_ORDER\_TYPE](orderproperties.md#enum_order_type) enumeration.

price

[in]  Price of trade operation.

percent=100

[in]  Percent of available margin (in %) to be used for trade operation.

Return Value

Maximum possible volume of trade operation.