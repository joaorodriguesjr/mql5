Market Info



[MQL5 Reference](index.md) / Market Info

[![Previous](previous.png)](ontesterpass.md) 
[![Next](next.png)](symbolstotal.md)

Getting Market Information

These are functions intended for receiving information about the market state.

| Function | Action |
| --- | --- |
| [SymbolsTotal](symbolstotal.md) | Returns the number of available (selected in Market Watch or all) symbols |
| [SymbolExist](symbolexist.md) | Checks if a symbol with a specified name exists |
| [SymbolName](symbolname.md) | Returns the name of a specified symbol |
| [SymbolSelect](symbolselect.md) | Selects a symbol in the Market Watch window or removes a symbol from the window |
| [SymbolIsSynchronized](symbolissynchronized.md) | Checks whether data of a selected symbol in the terminal are [synchronized](timeseries_access.md#synchronized) with data on the trade server |
| [SymbolInfoDouble](symbolinfodouble.md) | Returns the double value of the symbol for the corresponding property |
| [SymbolInfoInteger](symbolinfointeger.md) | Returns a value of an integer type (long, datetime, int or bool) of a specified symbol for the corresponding property |
| [SymbolInfoString](symbolinfostring.md) | Returns a value of the string type of a specified symbol for the corresponding property |
| [SymbolInfoMarginRate](symbolinfomarginrate.md) | Returns the margin rates depending on the order type and direction |
| [SymbolInfoTick](symbolinfotick.md) | Returns the current prices for the specified symbol in a variable of the [MqlTick](mqltick.md) type |
| [SymbolInfoSessionQuote](symbolinfosessionquote.md) | Allows receiving time of beginning and end of the specified quoting sessions for a specified symbol and day of week. |
| [SymbolInfoSessionTrade](symbolinfosessiontrade.md) | Allows receiving time of beginning and end of the specified trading sessions for a specified symbol and day of week. |
| [MarketBookAdd](marketbookadd.md) | Provides opening of Depth of Market for a selected symbol, and subscribes for receiving notifications of the DOM changes |
| [MarketBookRelease](marketbookrelease.md) | Provides closing of Depth of Market for a selected symbol, and cancels the subscription for receiving notifications of the DOM changes |
| [MarketBookGet](marketbookget.md) | Returns a structure array [MqlBookInfo](mqlbookinfo.md) containing records of the Depth of Market of a specified symbol |