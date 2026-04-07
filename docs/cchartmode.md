Mode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / Mode

[![Previous](previous.png)](cchartchartid.md) 
[![Next](next.png)](cchartforeground.md)

Mode (Get Method)

Gets the value of "Mode" property (bars, candles, or line).

```
ENUM_CHART_MODE  Mode() const
```

Return Value

Value of "Mode" property of the object assigned to the class instance. If there is no chart assigned, it returns [WRONG\_VALUE](otherconstants.md).

Mode (Set Method)

Sets new value for "Mode" property (bars, candles, or line).

```
bool  Mode(
   ENUM_CHART_MODE  mode      // chart mode
   )
```

Parameters

mode

[in]  Chart mode (candles, bars or line) of [ENUM\_CHART\_MODE](chart_view.md#enum_chart_mode) enumeration.

Return Value

true - successful, false - cannot change the mode.