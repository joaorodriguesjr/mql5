TimeCurrent



[MQL5 Reference](index.md)  /  [Date and Time](dateandtime.md) / TimeCurrent

[![Previous](previous.png)](dateandtime.md) 
[![Next](next.png)](timetradeserver.md)

TimeCurrent

Returns the last known server time, time of the last quote receipt for one of the symbols selected in the "Market Watch" window. In the [OnTick()](ontick.md) handler, this function returns the time of the received handled tick. In other cases (for example, call in [handlers](events.md) OnInit(), OnDeinit(), OnTimer() and so on) this is the [time of the last quote receipt](marketinfoconstants.md#lastticktime) for any symbol available in the "Market Watch" window, the time shown in the title of this window. The time value is formed on a trade server and does not depend on the time settings on your computer. There are 2 variants of the function.

Call without parameters

```
datetime  TimeCurrent();
```

Call with MqlDateTime type parameter

```
datetime  TimeCurrent(
   MqlDateTime&  dt_struct      // structure type variable
   );
```

Parameters

dt\_struct

[out] [MqlDateTime](mqldatetime.md) structure type variable.

Return Value

Value of [datetime](datetime.md) type

Note

If the MqlDateTime structure type variable has been passed as a parameter, it is filled accordingly.

To arrange high-resolution counters and timers, use the [GetTickCount()](gettickcount.md) function, which produces values in milliseconds.

During testing in the strategy tester, TimeCurrent() is simulated according to historical data.

Example:

```
void OnStart()
  {
//--- declare the MqlDateTime variable to be filled with date/time data and get the time of the last quote from the Market Watch window
   MqlDateTime tm={};
   datetime    time1=TimeCurrent();    // first form of call: time of the last quote for one of the symbols in the Market Watch window
   datetime    time2=TimeCurrent(tm);  // second form of call: time of the last quote for one of the symbols in the Market Watch window with filling of the MqlDateTime structure
   
//--- display the result of receiving the date/time and filling the structure with the corresponding data in the log
   PrintFormat("Tick time: %s\n- Year: %u\n- Month: %02u\n- Day: %02u\n- Hour: %02u\n- Min: %02u\n- Sec: %02u\n- Day of Year: %03u\n- Day of Week: %u (%s)",
               (string)time1, tm.year, tm.mon, tm.day, tm.hour, tm.min, tm.sec, tm.day_of_year, tm.day_of_week, EnumToString((ENUM_DAY_OF_WEEK)tm.day_of_week));
   /*
   result:
   Tick time: 2024.04.18 15:40:06
   - Year: 2024
   - Month: 04
   - Day: 18
   - Hour: 15
   - Min: 40
   - Sec: 06
   - Day of Year: 108
   - Day of Week: 4 (THURSDAY)
   */
  }
```