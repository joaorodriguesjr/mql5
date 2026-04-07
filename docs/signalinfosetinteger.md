SignalInfoSetInteger



[MQL5 Reference](index.md)  /  [Trade Signals](signals.md) / SignalInfoSetInteger

[![Previous](previous.png)](signalinfosetdouble.md) 
[![Next](next.png)](signalsubscribe.md)

SignalInfoSetInteger

Sets the value of [integer](integer.md) type property of signal copy settings.

```
bool  SignalInfoSetInteger(
   ENUM_SIGNAL_INFO_INTEGER     property_id,     // property identifier
   long                         value            // new value
   );
```

Parameters

property\_id

[in]  Signal copy settings property identifier. The value can be one of the values of the [ENUM\_SIGNAL\_INFO\_INTEGER](signalproperties.md#enum_signal_info_integer) enumeration.

value

[in]  The value of signal copy settings property.

Return Value

Returns true if property has been changed, otherwise returns false. To read more about the [error](errorcodes.md) call [GetLastError()](getlasterror.md).