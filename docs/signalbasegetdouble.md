SignalBaseGetDouble



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalBaseGetDouble

[![Previous](previous.png)](signals.md) 
[![Next](next.png)](signalbasegetinteger.md)

SignalBaseGetDouble

Returns the value of [double](double.md) type property for selected signal.

```
double  SignalBaseGetDouble(
   ENUM_SIGNAL_BASE_DOUBLE     property_id,     // property identifier
   );
```

Parameters

property\_id

[in]  Signal property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_BASE\_DOUBLE](signalproperties.md#enum_signal_base_double) enumeration.

Return Value

The value of [double](double.md) type property of the selected signal.