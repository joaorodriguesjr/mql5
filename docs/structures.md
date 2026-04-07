Data Structures



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md) / Data Structures

[![Previous](previous.png)](otherconstants.md) 
[![Next](next.png)](mqldatetime.md)

Data Structures

MQL5 Language offers 12 predefined [structures](classes.md):

* [MqlDateTime](mqldatetime.md) is intended for working with [date and time](dateandtime.md);

* [MqlParam](mqlparam.md) can send input parameters when creating a handle of the indicator using the [IndicatorCreate()](indicatorcreate.md) function;

* [MqlRates](mqlrates.md) is intended for manipulating the [historical data](series.md), it contains information about the price, volume and spread;
* [MqlBookInfo](mqlbookinfo.md) is intended for obtaining information about the [Depth of Market](marketinformation.md);
* [MqlTradeRequest](mqltraderequest.md) is used for creating a trade request for [trade operations](enum_trade_request_actions.md);

* [MqlTradeCheckResult](mqltradecheckresult.md) is intended for [checking](ordercheck.md) the prepared [trade request](mqltraderequest.md) before [sending](ordersend.md) it;

* [MqlTradeResult](mqltraderesult.md) contains a trade server reply to a [trade request](mqltraderequest.md), sent by [OrderSend()](ordersend.md) function;

* [MqlTradeTransaction](mqltradetransaction.md) contains description of a trade transaction;

* [MqlTick](mqltick.md) is designed for fast retrieval of the most requested information about current prices.

* [Economic calendar structures](mqlcalendar.md) are used to obtain data on the economic calendar events sent to the MetaTrader 5 platform in real time. [Economic calendar functions](calendar.md) allow analyzing macroeconomic parameters immediately after new reports are released, since relevant values are broadcast directly from the source with no delay.