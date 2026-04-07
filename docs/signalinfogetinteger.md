SignalInfoGetInteger



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalInfoGetInteger

[![Previous](previous.png)](signalinfogetdouble.md) 
[![Next](next.png)](signalinfogetstring.md)

SignalInfoGetInteger

Returns the value of [integer](integer.md) type property of signal copy settings.

```
long  SignalInfoGetInteger(
   ENUM_SIGNAL_INFO_INTEGER     property_id,     // property identifier
   );
```

Parameters

property\_id

[in]  Signal copy settings property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_INFO\_INTEGER](signalproperties.md#enum_signal_info_integer) enumeration.

Return Value

The value of [integer](integer.md) type property of signal copy settings.