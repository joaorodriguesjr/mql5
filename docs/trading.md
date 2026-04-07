Trade Functions



[MQL5 Reference](index.md) / Trade Functions

[![Previous](previous.png)](chartscreenshot.md) 
[![Next](next.png)](ordercalcmargin.md)

Trade Functions

This is the group of functions intended for managing trading activities.

Before you proceed to study the trade functions of the platform, you must have a clear understanding of the basic terms: order, deal and position:

* An order is an instruction given to a broker to buy or sell a financial instrument. There are two main types of orders: Market and Pending. In addition, there are special Take Profit and Stop Loss levels.
* A deal is the commercial exchange (buying or selling) of a financial security. Buying is executed at the demand price (Ask), and Sell is performed at the supply price (Bid). A deal can be opened as a result of market order execution or pending order triggering. Note that in some cases, execution of an order can result in several deals.
* A position is a trade obligation, i.e. the number of bought or sold contracts of a financial instrument. A long position is financial security bought expecting the security price go higher. A short position is an obligation to supply a security expecting the price will fall in future.

General information about trading operations is available in the [client terminal help](https://www.metatrader5.com/en/terminal/help/trading/general_concept "MetaTrader 5 Help").

Trading functions can be used in Expert Advisors and scripts. Trading functions can be called only if in the properties of the Expert Advisor or script the "Allow live trading" checkbox is enabled.

Trading can be allowed or prohibited depending on various factors described in the [Trade Permission](tradepermission.md) section.

| Function | Action |
| --- | --- |
| [OrderCalcMargin](ordercalcmargin.md) | Calculates the margin required for the specified order type, in the deposit currency |
| [OrderCalcProfit](ordercalcprofit.md) | Calculates the profit based on the parameters passed, in the deposit currency |
| [OrderCheck](ordercheck.md) | Checks if there are enough funds to execute the required [trade operation](enum_trade_request_actions.md). |
| [OrderSend](ordersend.md) | Sends [trade requests](mqltraderequest.md) to a server |
| [OrderSendAsync](ordersendasync.md) | Asynchronously sends [trade requests](enum_trade_request_actions.md) without waiting for the trade response of the trade server |
| [PositionsTotal](positionstotal.md) | Returns the number of open positions |
| [PositionGetSymbol](positiongetsymbol.md) | Returns the symbol corresponding to the open position |
| [PositionSelect](positionselect.md) | Chooses an open position for further working with it |
| [PositionSelectByTicket](positionselectbyticket.md) | Selects a position to work with by the ticket number specified in it |
| [PositionGetDouble](positiongetdouble.md) | Returns the requested property of an open position (double) |
| [PositionGetInteger](positiongetinteger.md) | Returns the requested property of an open position (datetime or int) |
| [PositionGetString](positiongetstring.md) | Returns the requested property of an open position (string) |
| [PositionGetTicket](positiongetticket.md) | Returns the ticket of the position with the specified index in the list of open positions |
| [OrdersTotal](orderstotal.md) | Returns the number of orders |
| [OrderGetTicket](ordergetticket.md) | Return the ticket of a corresponding order |
| [OrderSelect](orderselect.md) | Selects a order for further working with it |
| [OrderGetDouble](ordergetdouble.md) | Returns the requested property of the order (double) |
| [OrderGetInteger](ordergetinteger.md) | Returns the requested property of the order (datetime or int) |
| [OrderGetString](ordergetstring.md) | Returns the requested property of the order (string) |
| [HistorySelect](historyselect.md) | Retrieves the history of transactions and orders for the specified period of the server time |
| [HistorySelectByPosition](historyselectbyposition.md) | Requests the history of deals with a specified [position identifier](positionproperties.md#enum_position_property_integer). |
| [HistoryOrderSelect](historyorderselect.md) | Selects an order in the history for further working with it |
| [HistoryOrdersTotal](historyorderstotal.md) | Returns the number of orders in the history |
| [HistoryOrderGetTicket](historyordergetticket.md) | Return order ticket of a corresponding order in the history |
| [HistoryOrderGetDouble](historyordergetdouble.md) | Returns the requested property of an order in the history (double) |
| [HistoryOrderGetInteger](historyordergetinteger.md) | Returns the requested property of an order in the history (datetime or int) |
| [HistoryOrderGetString](historyordergetstring.md) | Returns the requested property of an order in the history (string) |
| [HistoryDealSelect](historydealselect.md) | Selects a deal in the history for further calling it through appropriate functions |
| [HistoryDealsTotal](historydealstotal.md) | Returns the number of deals in the history |
| [HistoryDealGetTicket](historydealgetticket.md) | Returns a ticket of a corresponding deal in the history |
| [HistoryDealGetDouble](historydealgetdouble.md) | Returns the requested property of a deal in the history (double) |
| [HistoryDealGetInteger](historydealgetinteger.md) | Returns the requested property of a deal in the history (datetime or int) |
| [HistoryDealGetString](historydealgetstring.md) | Returns the requested property of a deal in the history (string) |