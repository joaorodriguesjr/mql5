Date and Time



[MQL5 Reference](index.md) / Date and Time

[![Previous](previous.png)](stringtrimright.md) 
[![Next](next.png)](timecurrent.md)

Date and Time

This is the group of functions for working with data of [datetime](datetime.md) type (an integer that represents the number of seconds elapsed from 0 hours of January 1, 1970).

To arrange high-resolution counters and timers, use the [GetTickCount()](gettickcount.md) function, which produces values in milliseconds.

| Function | Action |
| --- | --- |
| [TimeCurrent](timecurrent.md) | Returns the last known server time (time of the last quote receipt) in the datetime format |
| [TimeTradeServer](timetradeserver.md) | Returns the current calculation time of the trade server |
| [TimeLocal](timelocal.md) | Returns the local computer time in datetime format |
| [TimeGMT](timegmt.md) | Returns GMT in datetime format with the Daylight Saving Time by local time of the computer, where the client terminal is running |
| [TimeDaylightSavings](timedaylightsavings.md) | Returns the sign of Daylight Saving Time switch |
| [TimeGMTOffset](timegmtoffset.md) | Returns the current difference between GMT time and the local computer time in seconds, taking into account DST switch |
| [TimeToStruct](timetostruct.md) | Converts a datetime value into a variable of MqlDateTime structure type |
| [StructToTime](structtotime.md) | Converts a variable of MqlDateTime structure type into a datetime value |