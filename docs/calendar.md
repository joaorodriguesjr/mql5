Economic Calendar



[MQL5 Reference](index.md) / Economic Calendar

[![Previous](previous.png)](marketbookget.md) 
[![Next](next.png)](calendarcountrybyid.md)

Economic calendar functions

This section describes the functions for working with the [economic calendar](https://www.metatrader5.com/en/terminal/help/charts_analysis/fundamental) available directly in the MetaTrader platform. The economic calendar is a ready-made encyclopedia featuring descriptions of macroeconomic indicators, their release dates and degrees of importance. Relevant values of macroeconomic indicators are sent to the MetaTrader platform right at the moment of publication and are displayed on a chart as tags allowing you to visually track the required indicators by countries, currencies and importance.

All functions for working with the economic calendar use the trade server time ([TimeTradeServer](timetradeserver.md)). This means that the time in the [MqlCalendarValue](mqlcalendar.md#mqlcalendarvalue) structure and the time inputs in the [CalendarValueHistoryByEvent](calendarvaluehistorybyevent.md)/[CalendarValueHistory](calendarvaluehistory.md) functions are set in a trade server timezone, rather than a user's local time.

[Economic calendar functions](calendar.md) allow conducting the auto analysis of incoming events according to custom importance criteria from a perspective of necessary countries/currencies.

| Function | Action |
| --- | --- |
| [CalendarCountryById](calendarcountrybyid.md) | Get a country description by its ID |
| [CalendarEventById](calendareventbyid.md) | Get an event description by its ID |
| [CalendarValueById](calendarvaluebyid.md) | Get an event value description by its ID |
| [CalendarCountries](calendarcountries.md) | Get the array of country names available in the calendar |
| [CalendarEventByCountry](calendareventbycountry.md) | Get the array of descriptions of all events available in the calendar by a specified country code |
| [CalendarEventByCurrency](calendareventbycurrency.md) | Get the array of descriptions of all events available in the calendar by a specified currency |
| [CalendarValueHistoryByEvent](calendarvaluehistorybyevent.md) | Get the array of values for all events in a specified time range by an event ID |
| [CalendarValueHistory](calendarvaluehistory.md) | Get the array of values for all events in a specified time range with the ability to sort by country and/or currency |
| [CalendarValueLastByEvent](calendarvaluelastbyevent.md) | Get the array of event values by its ID since the calendar database status with a specified change\_id |
| [CalendarValueLast](calendarvaluelast.md) | Get the array of values for all events with the ability to sort by country and/or currency since the calendar database status with a specified change\_id |