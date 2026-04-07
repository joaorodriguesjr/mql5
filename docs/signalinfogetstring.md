SignalInfoGetString



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalInfoGetString

[![Previous](previous.png)](signalinfogetinteger.md) 
[![Next](next.png)](signalinfosetdouble.md)

SignalInfoGetString

Returns the value of [string](stringconst.md) type property of signal copy settings.

```
string  SignalInfoGetString(
   ENUM_SIGNAL_INFO_STRING     property_id,     // property identifier
   );
```

Parameters

property\_id

[in]  Signal copy settings property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_INFO\_STRING](signalproperties.md#enum_signal_info_string) enumeration.

Return Value

The value of [string](stringconst.md) type property of signal copy settings.