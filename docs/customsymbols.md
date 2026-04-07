Custom Symbols



[MQL5 Reference](index.md) / Custom Symbols

[![Previous](previous.png)](ispread.md) 
[![Next](next.png)](customsymbolcreate.md)

Custom symbols

Functions for creating and editing the custom symbol properties.

When connecting the terminal to a certain trade server, a user is able to [work with time series](series.md) of the financial symbols provided by a broker. Available financial symbols are displayed as a list in the Market Watch window. A separate group of functions allows [receiving data on the symbol properties](marketinformation.md), trading sessions and market depth updates.

The group of functions described in this section allows creating custom symbols. To do this, users are able to apply the trade server's existing symbols, text files or external data sources.

| Function | Action |
| --- | --- |
| [CustomSymbolCreate](customsymbolcreate.md) | Create a custom symbol with the specified name in the specified group |
| [CustomSymbolDelete](customsymboldelete.md) | Delete a custom symbol with the specified name |
| [CustomSymbolSetInteger](customsymbolsetinteger.md) | Set the integer type property value for a custom symbol |
| [CustomSymbolSetDouble](customsymbolsetdouble.md) | Set the real type property value for a custom symbol |
| [CustomSymbolSetString](customsymbolsetstring.md) | Set the string type property value for a custom symbol |
| [CustomSymbolSetMarginRate](customsymbolsetmarginrate.md) | Set the margin rates depending on the order type and direction for a custom symbol |
| [CustomSymbolSetSessionQuote](customsymbolsetsessionquote.md) | Set the start and end time of the specified quotation session for the specified symbol and week day |
| [CustomSymbolSetSessionTrade](customsymbolsetsessiontrade.md) | Set the start and end time of the specified trading session for the specified symbol and week day |
| [CustomRatesDelete](customratesdelete.md) | Delete all bars from the price history of the custom symbol in the specified time interval |
| [CustomRatesReplace](customratesreplace.md) | Fully replace the price history of the custom symbol within the specified time interval with the data from the MqlRates type array |
| [CustomRatesUpdate](customratesupdate.md) | Add missing bars to the custom symbol history and replace existing data with the ones from the MqlRates type array |
| [CustomTicksAdd](customticksadd.md) | Adds data from an array of the MqlTick type to the price history of a custom symbol. The custom symbol must be selected in the Market Watch window |
| [CustomTicksDelete](customticksdelete.md) | Delete all ticks from the price history of the custom symbol in the specified time interval |
| [CustomTicksReplace](customticksreplace.md) | Fully replace the price history of the custom symbol within the specified time interval with the data from the MqlTick type array |
| [CustomBookAdd](custombookadd.md) | Passes the status of the Depth of Market for a custom symbol |