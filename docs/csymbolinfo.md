CSymbolInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CSymbolInfo

[![Previous](previous.png)](caccountinfomaxlotcheck.md) 
[![Next](next.png)](csymbolinforefresh.md)

CSymbolInfo

CSymbolInfo is a class for easy access to the symbol properties.

Description

CSymbolInfo class provides access to the symbol properties.

Declaration

```
   class CSymbolInfo : public CObject
```

Title

```
   #include <Trade\SymbolInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CSymbolInfo |

Class methods by groups

| Controlling |  |
| --- | --- |
| [Refresh](csymbolinforefresh.md) | Refreshes the symbol data |
| [RefreshRates](csymbolinforefreshrates.md) | Refreshes the symbol quotes |
| Properties |  |
| [Name](csymbolinfoname.md) | Gets/sets symbol name |
| [Select](csymbolinfoselect.md) | Gets/sets the "Market Watch" symbol flag |
| [IsSynchronized](csymbolinfoissynchronized.md) | Checks the symbol synchronization with server |
| Volumes |  |
| [Volume](csymbolinfovolume.md) | Gets the volume of last deal |
| [VolumeHigh](csymbolinfovolumehigh.md) | Gets the maximal volume for a day |
| [VolumeLow](csymbolinfovolumelow.md) | Gets the minimal volume for a day |
| Miscellaneous |  |
| [Time](csymbolinfotime.md) | Gets the time of last quote |
| [Spread](csymbolinfospread.md) | Gets the amount of spread (in points) |
| [SpreadFloat](csymbolinfospreadfloat.md) | Gets the flag of floating spread |
| [TicksBookDepth](csymbolinfoticksbookdepth.md) | Gets the depth of ticks saving |
| Levels |  |
| [StopsLevel](csymbolinfostopslevel.md) | Gets the minimal indent for orders (in points) |
| [FreezeLevel](csymbolinfofreezelevel.md) | Gets the distance of freezing trade operations (in points) |
| Bid prices |  |
| [Bid](csymbolinfobid.md) | Gets the current Bid price |
| [BidHigh](csymbolinfobidhigh.md) | Gets the maximal Bid price for a day |
| [BidLow](csymbolinfobidlow.md) | Gets the minimal Bid price for a day |
| Ask prices |  |
| [Ask](csymbolinfoask.md) | Gets the current Ask price |
| [AskHigh](csymbolinfoaskhigh.md) | Gets the maximal Ask price for a day |
| [AskLow](csymbolinfoasklow.md) | Gets the minimal Ask price for a day |
| Prices |  |
| [Last](csymbolinfolast.md) | Gets the current Last price |
| [LastHigh](csymbolinfolasthigh.md) | Gets the maximal Last price for a day |
| [LastLow](csymbolinfolastlow.md) | Gets the minimal Last price for a day |
| Trade modes |  |
| [TradeCalcMode](csymbolinfotradecalcmode.md) | Gets the mode of contract cost calculation |
| [TradeCalcModeDescription](csymbolinfotradecalcmodedescription.md) | Gets the mode of contract cost calculation as a string |
| [TradeMode](csymbolinfotrademode.md) | Gets the type of order execution |
| [TradeModeDescription](csymbolinfotrademodedescription.md) | Gets the type of order execution as a string |
| [TradeExecution](csymbolinfotradeexecution.md) | Gets the trade execution mode |
| [TradeExecutionDescription](csymbolinfotradeexecutiondescription.md) | Gets the execution mode as a string |
| Swaps |  |
| [SwapMode](csymbolinfoswapmode.md) | Gets the swap calculation mode |
| [SwapModeDescription](csymbolinfoswapmodedescription.md) | Gets the swap calculation mode as a string |
| [SwapRollover3days](csymbolinfoswaprollover3days.md) | Gets the day of triple swap charge |
| [SwapRollover3daysDescription](csymbolinfoswaprollover3daysdescription.md) | Gets the day of triple swap charge as a string |
| Margins and flags |  |
| [MarginInitial](csymbolinfomargininitial.md) | Gets the value of initial margin |
| [MarginMaintenance](csymbolinfomarginmaintenance.md) | Gets the value of maintenance margin |
| [MarginLong](csymbolinfomarginlong.md) | Gets the rate of margin charging for long positions |
| [MarginShort](csymbolinfomarginshort.md) | Gets the rate of margin charging for short positions |
| [MarginLimit](csymbolinfomarginlimit.md) | Gets the rate of margin charging for Limit orders |
| [MarginStop](csymbolinfomarginstop.md) | Gets the rate of margin charging for Stop orders |
| [MarginStopLimit](csymbolinfomarginstoplimit.md) | Gets the rate of margin charging for StopLimit orders |
| [TradeTimeFlags](csymbolinfotradetimeflags.md) | Gets the flags of allowed expiration modes |
| [TradeFillFlags](csymbolinfotradefillflags.md) | Gets the flags of allowed filling modes |
| Quantization |  |
| [Digits](csymbolinfodigits.md) | Gets the number of digits after period |
| [Point](csymbolinfopoint.md) | Gets the value of one point |
| [TickValue](csymbolinfotickvalue.md) | Gets the tick value (minimal change of price) |
| [TickValueProfit](csymbolinfotickvalueprofit.md) | Gets the calculated tick price for a profitable position |
| [TickValueLoss](csymbolinfotickvalueloss.md) | Gets the calculated tick price for a losing position |
| [TickSize](csymbolinfoticksize.md) | Gets the minimal change of price |
| Contracts sizes |  |
| [ContractSize](csymbolinfocontractsize.md) | Gets the amount of trade contract |
| [LotsMin](csymbolinfolotsmin.md) | Gets the minimal volume to close a deal |
| [LotsMax](csymbolinfolotsmax.md) | Gets the maximal volume to close a deal |
| [LotsStep](csymbolinfolotsstep.md) | Gets the minimal step of volume change to close a deal |
| [LotsLimit](csymbolinfolotslimit.md) | Gets the maximal allowed volume of opened position and pending orders (direction insensitive) for one symbol |
| Swaps sizes |  |
| [SwapLong](csymbolinfoswaplong.md) | Gets the value of long position swap |
| [SwapShort](csymbolinfoswapshort.md) | Gets the value of short position swap |
| Text properties |  |
| [CurrencyBase](csymbolinfocurrencybase.md) | Gets the name of symbol base currency |
| [CurrencyProfit](csymbolinfocurrencyprofit.md) | Gets the profit currency name |
| [CurrencyMargin](csymbolinfocurrencymargin.md) | Gets the margin currency name |
| [Bank](csymbolinfobank.md) | Gets the name of current quote source |
| [Description](csymbolinfodescription.md) | Gets the string description of symbol |
| [Path](csymbolinfopath.md) | Gets the path in symbols tree |
| Symbol properties |  |
| [SessionDeals](csymbolinfosessiondeals.md) | Gets the number of deals in the current session |
| [SessionBuyOrders](csymbolinfosessionbuyorders.md) | Gets the number of Buy orders at the moment |
| [SessionSellOrders](csymbolinfosessionsellorders.md) | Gets the number of Sell orders at the moment |
| [SessionTurnover](csymbolinfosessionturnover.md) | Gets the summary of turnover of the current session |
| [SessionInterest](csymbolinfosessioninterest.md) | Gets the summary of open interest of the current session |
| [SessionBuyOrdersVolume](csymbolinfosessionbuyordersvolume.md) | Gets the current volume of Buy orders |
| [SessionSellOrdersVolume](csymbolinfosessionsellordersvolume.md) | Gets the current volume of Sell orders |
| [SessionOpen](csymbolinfosessionopen.md) | Gets the open price of the current session |
| [SessionClose](csymbolinfosessionclose.md) | Gets the close price of the current session |
| [SessionAW](csymbolinfosessionaw.md) | Gets the average weighted price of the current session |
| [SessionPriceSettlement](csymbolinfosessionpricesettlement.md) | Gets the settlement price of the current session |
| [SessionPriceLimitMin](csymbolinfosessionpricelimitmin.md) | Gets the minimal price of the current session |
| [SessionPriceLimitMax](csymbolinfosessionpricelimitmax.md) | Gets the maximal price of the current session |
| Access to MQL5 API functions |  |
| [InfoInteger](csymbolinfoinfointeger.md) | Gets the value of specified integer type property |
| [InfoDouble](csymbolinfoinfodouble.md) | Gets the value of specified double type property |
| [InfoString](csymbolinfoinfostring.md) | Gets the value of specified string type property |
| Service functions |  |
| [NormalizePrice](csymbolinfonormalizeprice.md) | Returns the value of price, normalized using the symbol properties |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |