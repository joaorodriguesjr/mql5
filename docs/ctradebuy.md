Buy



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / Buy

[![Previous](previous.png)](ctradepositioncloseby.md) 
[![Next](next.png)](ctradesell.md)

Buy

Opens a long position with specified parameters.

```
bool  Buy(
   double        volume,          // position volume
   const string  symbol=NULL,     // symbol
   double        price=0.0,       // execution price
   double        sl=0.0,          // stop loss price
   double        tp=0.0,          // take profit price
   const string  comment=""       // comment
   )
```

Parameters

volume

[in]  Requested position volume.

symbol=[NULL](void.md)

[in]  Position symbol. If it is not specified, the current symbol will be used.

price=0.0

[in]  Price. If the price is not specified, the current market Ask price will be used.

sl=0.0

[in]  Stop Loss price.

tp=0.0

[in]  Take Profit price.

comment=""

[in]  Comment.

Return Value

true - successful check of the structures, otherwise - false.

Note

Successful completion of the Buy(...) method does not always mean successful execution of the trade operation. It is necessary to check the result of trade request (trade server [return code](enum_trade_return_codes.md)) using [ResultRetcode()](ctraderesultretcode.md) and value returned by [ResultDeal()](ctraderesultdeal.md).