iBars



[MQL5 Reference](index.md)  /  [Timeseries and Indicators Access](series.md) / iBars

[![Previous](previous.png)](copyticksrange.md) 
[![Next](next.png)](ibarshift.md)

iBars

Returns the number of bars of a corresponding symbol and period, available in history.

```
int  iBars(
   const string           symbol,          // Symbol
   ENUM_TIMEFRAMES        timeframe        // Period
   );
```

Parameters

symbol

[in]  The symbol name of the financial instrument. [NULL](otherconstants.md) means the current symbol.

timeframe

[in]  Period. It can be one of the values of the [ENUM\_TIMEFRAMES](enum_timeframes.md) enumeration. 0 means the current chart period.

Return Value

The number of bars of a corresponding symbol and period, available in history, but no more than allowed by the "Max bars in chart" parameter in platform settings.

Example:

```
  Print("Bar count on the 'EURUSD,H1' is ",iBars("EURUSD",PERIOD_H1));
```

See also

[Bars](bars.md)