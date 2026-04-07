History Database Properties



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Trade Constants](tradingconstants.md) / History Database Properties

[![Previous](previous.png)](tradingconstants.md) 
[![Next](next.png)](orderproperties.md)

History Database Properties

When accessing [timeseries](series.md) the [SeriesInfoInteger()](seriesinfointeger.md) function is used for obtaining additional [symbol information](marketinfoconstants.md). Identifier of a required property is passed as the function parameter. The identifier can be one of values of ENUM\_SERIES\_INFO\_INTEGER.

ENUM\_SERIES\_INFO\_INTEGER

| Identifier | Description | Type |
| --- | --- | --- |
| SERIES\_BARS\_COUNT | Bars count for the symbol-period for the current moment | long |
| SERIES\_FIRSTDATE | The very first date for the symbol-period for the current moment | datetime |
| SERIES\_LASTBAR\_DATE | Open time of the last bar of the symbol-period | datetime |
| SERIES\_SERVER\_FIRSTDATE | The very first date in the history of the symbol on the server regardless of the timeframe | datetime |
| SERIES\_TERMINAL\_FIRSTDATE | The very first date in the history of the symbol in the client terminal, regardless of the timeframe | datetime |
| SERIES\_SYNCHRONIZED | Symbol/period data synchronization flag for the current moment | bool |