SignalBaseGetInteger



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalBaseGetInteger

[![Previous](previous.png)](signalbasegetdouble.md) 
[![Next](next.png)](signalbasegetstring.md)

SignalBaseGetInteger

Returns the value of [integer](integer.md) type property for selected signal.

```
long  SignalBaseGetInteger(
   ENUM_SIGNAL_BASE_INTEGER     property_id,     // property identifier
   );
```

Parameters

property\_id

[in]  Signal property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_BASE\_INTEGER](signalproperties.md#enum_signal_base_integer) enumeration.

Return Value

The value of [integer](integer.md) type property of the selected signal.