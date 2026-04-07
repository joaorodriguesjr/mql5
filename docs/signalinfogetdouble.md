SignalInfoGetDouble



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalInfoGetDouble

[![Previous](previous.png)](signalbasetotal.md) 
[![Next](next.png)](signalinfogetinteger.md)

SignalInfoGetDouble

Returns the value of [double](double.md) type property of signal copy settings.

```
double  SignalInfoGetDouble(
   ENUM_SIGNAL_INFO_DOUBLE     property_id,     // property identifier
   );
```

Parameters

property\_id

[in]  Signal copy settings property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_INFO\_DOUBLE](signalproperties.md#enum_signal_info_double) enumeration.

Return Value

The value of [double](double.md) type property of signal copy settings.