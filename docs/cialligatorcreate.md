Create



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Bill Williams Indicators](bwindicators.md)  /  [CiAlligator](cialligator.md) / Create

[![Previous](previous.png)](cialligatorapplied.md) 
[![Next](next.png)](cialligatorjaw.md)

Create

Creates the indicator with specified parameters. Use [Refresh()](cindicatorrefresh.md) and [GetData()](cindicatorgetdata.md) to update and get the indicator values.

```
bool  Create(
   string           symbol,           // symbol
   ENUM_TIMEFRAMES  period,           // period
   int              jaw_period,       // jaws period
   int              jaw_shift,        // jaws shift
   int              teeth_period,     // teeth period
   int              teeth_shift,      // teeth shift
   int              lips_period,      // lips period
   int              lips_shift,       // lips shift
   ENUM_MA_METHOD   ma_method,        // averaging method
   int              applied           // price type, handle
   )
```

Parameters

symbol

[in]  Symbol.

period

[in]  Timeframe ([ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration value).

jaw\_period

[in]  Jaws averaging period.

jaw\_shift

[in]  Jaws horizontal shift.

teeth\_period

[in]  Teeth averaging period.

teeth\_shift

[in]  Teeth horizontal shift.

lips\_period

[in]  Lips averaging period.

lips\_shift

[in]  Lips horizontal shift.

ma\_method

[in]  Moving average method ([ENUM\_MA\_METHOD](enum_ma_method.md) enumeration value).

applied

[in]  Price type, handle to apply.

Return Value

true - successful, false - cannot create the indicator.