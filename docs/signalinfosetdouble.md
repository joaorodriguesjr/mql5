SignalInfoSetDouble



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalInfoSetDouble

[![Previous](previous.png)](signalinfogetstring.md) 
[![Next](next.png)](signalinfosetinteger.md)

SignalInfoSetDouble

Sets the value of [double](double.md) type property of signal copy settings.

```
bool  SignalInfoSetDouble(
   ENUM_SIGNAL_INFO_DOUBLE      property_id,     // property identifier
   double                       value            // new value
   );
```

Parameters

property\_id

[in]  Signal copy settings property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_INFO\_DOUBLE](signalproperties.md#enum_signal_info_double) enumeration.

value

[in]  The value of signal copy settings property.

Return Value

Returns true if property has been changed, otherwise returns false. To read more about the [error](errorcodes.md) call [GetLastError()](getlasterror.md).