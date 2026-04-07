SignalBaseGetString



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalBaseGetString

[![Previous](previous.png)](signalbasegetinteger.md) 
[![Next](next.png)](signalbaseselect.md)

SignalBaseGetString

Returns the value of [string](stringconst.md) type property for selected signal.

```
string  SignalBaseGetString(
   ENUM_SIGNAL_BASE_STRING     property_id,     // property identifier
   );
```

Parameters

property\_id

[in]  Signal property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_BASE\_STRING](signalproperties.md#enum_signal_base_string) enumeration.

Return Value

The value of [string](stringconst.md) type property of the selected signal.