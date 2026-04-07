SignalSubscribe



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalSubscribe

[![Previous](previous.png)](signalinfosetinteger.md) 
[![Next](next.png)](signalunsubscribe.md)

SignalSubscribe

Subscribes to the trading signal.

```
bool  SignalSubscribe(
   long     signal_id     // signal id 
   );
```

Parameters

signal\_id

[in]  Signal identifier.

Return Value

Returns true if subscription was successful, otherwise returns false. To read more about the [error](errorcodes.md) call [GetLastError()](getlasterror.md).