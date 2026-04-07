Trade Orders in DOM



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Trade Constants](tradingconstants.md) / Trade Orders in DOM

[![Previous](previous.png)](enum_trade_transaction_type.md) 
[![Next](next.png)](signalproperties.md)

Trade Orders in Depth Of Market

For equity securities, the Depth of Market window is available, where you can see the current Buy and Sell orders. Desired direction of a trade operation, required amount and requested price are specified for each order.

To obtain information about the current state of the DOM by MQL5 means, the [MarketBookGet()](marketbookget.md) function is used, which places the DOM "screen shot" into the [MqlBookInfo](mqlbookinfo.md) array of structures. Each element of the array in the type field contains information about the direction of the order - the value of the ENUM\_BOOK\_TYPE enumeration.

ENUM\_BOOK\_TYPE

| Identifier | Description |
| --- | --- |
| BOOK\_TYPE\_SELL | Sell order (Offer) |
| BOOK\_TYPE\_BUY | Buy order (Bid) |
| BOOK\_TYPE\_SELL\_MARKET | Sell order by Market |
| BOOK\_TYPE\_BUY\_MARKET | Buy order by Market |

See also

[Structures and classes](classes.md), [Structure of the DOM](mqlbookinfo.md), [Trade operation types](enum_trade_request_actions.md), [Market Info](marketinformation.md)