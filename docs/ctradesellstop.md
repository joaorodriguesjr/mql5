SellStop



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / SellStop

[![Previous](previous.png)](ctradeselllimit.md) 
[![Next](next.png)](ctraderequest.md)

SellStop

Places the pending order of Sell Stop type (sell at the price lower than current market price) with specified parameters.

```
bool  SellStop(
   double                volume,                       // order volume
   double                price,                        // order price
   const string          symbol=NULL,                  // symbol
   double                sl=0.0,                       // stop loss price
   double                tp=0.0,                       // take profit price
   ENUM_ORDER_TYPE_TIME  type_time=ORDER_TIME_GTC,     // order lifetime
   datetime              expiration=0,                 // order expiration time
   const string          comment=""                    // comment
   )
```

Parameters

volume

[in]  Requested order volume.

price

[in]  Order price.

symbol=[NULL](void.md)

[in]  Order symbol. If the symbol is not specified, the current symbol will be used.

sl=0.0

[in]  Stop Loss price.

tp=0.0

[in]  Take Profit price.

type\_time=[ORDER\_TIME\_GTC](orderproperties.md#enum_order_type_time)

[in]  Order lifetime from [ENUM\_ORDER\_TYPE\_TIME](orderproperties.md#enum_order_type_time) enumeration.

expiration=0

[in]  Order expiration time (used only if type\_time=[ORDER\_TIME\_SPECIFIED](orderproperties.md#enum_order_type_time)).

comment=""

[in]  Order comment.

Return Value

true - successful check of the structures, otherwise - false.

Note

Successful completion of the SellStop(...) method does not always mean successful execution of the trade operation. It is necessary to check the result of trade request (trade server [return code](enum_trade_return_codes.md)) using [ResultRetcode()](ctraderesultretcode.md) and value returned by [ResultOrder()](ctraderesultorder.md).