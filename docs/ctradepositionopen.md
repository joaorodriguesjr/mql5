PositionOpen



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / PositionOpen

[![Previous](previous.png)](ctradeorderdelete.md) 
[![Next](next.png)](ctradepositionmodify.md)

PositionOpen

Opens a position with the specified parameters.

```
bool  PositionOpen(
   const string     symbol,         // symbol
   ENUM_ORDER_TYPE  order_type,     // order type to open position
   double           volume,         // position volume
   double           price,          // execution price
   double           sl,             // Stop Loss price
   double           tp,             // Take Profit price
   const string     comment=""      // comment
   )
```

Parameters

symbol

[in]  Name of trade instrument, by which it is intended to open position.

order\_type

[in]  Order type (trade operation) to open position from [ENUM\_ORDER\_TYPE](orderproperties.md#enum_order_type) enumeration.

volume

[in] Requested position volume.

price

[in] Price at which the position must be opened.

sl

[in] Price at which the Stop Loss will trigger.

tp

[in] Price at which the Take Profit will trigger.

comment=""

[in]  Position comment.

Return Value

true - successful check of the basic structures, otherwise - false.

Note

Successful completion of the PositionOpen(...) method does not always mean successful execution of the trade operation. It is necessary to check the result of trade request (trade server return code) using [ResultRetcode()](ctraderesultretcode.md) and value returned by [ResultDeal()](ctraderesultdeal.md).