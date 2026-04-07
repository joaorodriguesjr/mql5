OrderProfitCheck



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CAccountInfo](caccountinfo.md) / OrderProfitCheck

[![Previous](previous.png)](caccountinfostring.md) 
[![Next](next.png)](caccountinfomargincheck.md)

OrderProfitCheck

The function calculates the profit for the current account, based on the parameters passed. The function is used for pre-evaluation of the result of a trade operation. The value is returned in the account currency.

```
double  OrderProfitCheck(
   const string        symbol,              // symbol
   ENUM_ORDER_TYPE     trade_operation,     // order type (ORDER_TYPE_BUY or ORDER_TYPE_SELL)
   double              volume,              // volume
   double              price_open,          // position open price
   double              price_close          // position close price
   ) const
```

Parameters

symbol

[in]  Symbol for trade operation.

trade\_operation

[in] Type of trade operation from [ENUM\_ORDER\_TYPE](orderproperties.md#enum_order_type) enumeration.

volume

[in]  Volume of trade operation.

price\_open

[in]  Open price.

price\_close

[in]  Close price.

Return Value

If successful, it returns amount of profit or [EMPTY\_VALUE](typeconstants.md) in the case of error.