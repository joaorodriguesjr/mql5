SetAsyncMode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / SetAsyncMode

[![Previous](previous.png)](ctradesettypefillingbysymbol.md) 
[![Next](next.png)](ctradesetmargingmode.md)

SetAsyncMode

Sets asynchronous mode for trade operations.

```
void  SetAsyncMode(
   bool  mode      // asynchronous mode flag
   )
```

Parameters

mode

[in]  Asynchronous mode flag.

Return Value

None.

Note

This mode is used for asynchronous (without waiting for the trade server's response to a sent request) trade operations (see [OrderSendAsync](ordersendasync.md)).