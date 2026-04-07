CExpert



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md) / CExpert

[![Previous](previous.png)](cexpertbasecomparemagic.md) 
[![Next](next.png)](cexpertinit.md)

CExpert

CExpert is a base class for trading strategies.

It already has some elementary trading "skills". It has built-in algorithms for working with time series and indicators and a set of virtual methods for trading strategy.

How to use it:

1. Prepare an algorithm of the strategy;  
2. Create your own class, inherited from CExpert class;  
3. Override the virtual methods in your class with your own algorithms.

Description

The CExpert class is a set of virtual methods for implementation of trading strategies.

Note

A position is recognized as belonging to an Expert Advisor and managed by it based on the pair of properties m\_symbol and m\_magic. In the "hedging" mode, multiple positions can be opened for the same symbol, therefore the m\_magic value is important.

Declaration

```
   class CExpert : public CExpertBase
```

Title

```
   #include <Expert\Expert.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            CExpert |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| [Init](cexpertinit.md) | Class instance initialization method |
| virtual [InitSignal](cexpertinitsignal.md) | Initializes Trading Signal object |
| virtual [InitTrailing](cexpertinittrailing.md) | Initializes Trailing Stop object |
| virtual [InitMoney](cexpertinitmoney.md) | Initializes Money Management object |
| virtual [InitTrade](cexpertinittrade.md) | Initializes Trade object |
| virtual [ValidationSettings](cexpertvalidationsettings.md) | Checks the settings |
| virtual [InitIndicators](cexpertinitindicators.md) | Initializes indicators and timeseries |
| virtual [InitParameters](cexpertinitparameters.md) | Expert Advisor parameters initialization method |
| virtual [Deinit](cexpertdeinit.md) | Class instance deinitialization method |
| virtual [DeinitSignal](cexpertdeinitsignal.md) | Deinitializes Trading Signal object |
| virtual [DeinitTrailing](cexpertdeinittrailing.md) | Deinitializes Trailing Stop object |
| virtual [DeinitMoney](cexpertdeinitmoney.md) | Deinitializes Money Management object |
| virtual [DeinitTrade](cexpertdeinittrade.md) | Deinitializes Trade object |
| virtual [DeinitIndicators](cexpertdeinitindicators.md) | Deinitializes indicators and timeseries |
| Parameters |  |
| [Magic](cexpertmagic.md) | Sets the Expert Advisor ID |
| [MaxOrders](cexpertmaxorders.md) | Gets/sets the maximum amount of allowed orders |
| [OnTickProcess](cexpertontickprocess.md) | Sets a flag to proceed the "OnTick" event |
| [OnTradeProcess](cexpertontradeprocess.md) | Sets a flag to proceed the "OnTrade" event |
| [OnTimerProcess](cexpertontimerprocess.md) | Sets a flag to proceed the "OnTimer" event |
| [OnChartEventProcess](cexpertoncharteventprocess.md) | Sets a flag to proceed the "OnChartEvent" event |
| [OnBookEventProcess](cexpertonbookeventprocess.md) | Sets a flag to proceed the "OnBookEvent" event |
| Event Processing Methods |  |
| [OnTick](cexpertontick.md) | OnTick event handler |
| [OnTrade](cexpertontrade.md) | OnTrade event handler |
| [OnTimer](cexpertontimer.md) | OnTimer event handler |
| [OnChartEvent](cexpertonchartevent.md) | OnChartEvent event handler |
| [OnBookEvent](cexpertonbookevent.md) | OnBookEvent event handler |
| Update Methods |  |
| [Refresh](cexpertrefresh.md) | Updates all data |
| Processing |  |
| [Processing](cexpertprocessing.md) | Main processing algorithm |
| Market Entry Methods |  |
| [CheckOpen](cexpertcheckopen.md) | Checks position opening conditions |
| [CheckOpenLong](cexpertcheckopenlong.md) | Checks conditions to open long position |
| [CheckOpenShort](cexpertcheckopenshort.md) | Checks conditions to open short position |
| [OpenLong](cexpertopenlong.md) | Opens a long position |
| [OpenShort](cexpertopenshort.md) | Opens a short position |
| Market Exit Methods |  |
| [CheckClose](cexpertcheckclose.md) | Checks conditions to close current position |
| [CheckCloseLong](cexpertcheckcloselong.md) | Checks conditions to close long position |
| [CheckCloseShort](cexpertcheckcloseshort.md) | Checks conditions to close short position |
| [CloseAll](cexpertcloseall.md) | Closes the opened position and deletes all orders |
| [Close](cexpertclose.md) | Closes the opened position |
| [CloseLong](cexpertcloselong.md) | Closes the long position |
| [CloseShort](cexpertcloseshort.md) | Closes the short position |
| Position Reverse Methods |  |
| [CheckReverse](cexpertcheckreverse.md) | Checks conditions to reverse opened position |
| [CheckReverseLong](cexpertcheckreverselong.md) | Checks conditions to reverse long position |
| [CheckReverseShort](cexpertcheckreverseshort.md) | Checks conditions to reverse short position |
| [ReverseLong](cexpertreverselong.md) | Performs reverse operation of long position |
| [ReverseShort](cexpertreverseshort.md) | Performs reverse operation of short position |
| Position/Order Trailing Methods |  |
| [CheckTrailingStop](cexpertchecktrailingstop.md) | Checks conditions to modify position parameters |
| [CheckTrailingStopLong](cexpertchecktrailingstoplong.md) | Checks Trailing Stop conditions of long position |
| [CheckTrailingStopShort](cexpertchecktrailingstopshort.md) | Checks Trailing Stop conditions of short position |
| [TrailingStopLong](cexperttrailingstoplong.md) | Performs Trailing Stop for long position |
| [TrailingStopShort](cexperttrailingstopshort.md) | Performs Trailing Stop for short position |
| [CheckTrailingOrderLong](cexpertchecktrailingorderlong.md) | Checks Trailing Stop conditions of Buy Limit/Stop order |
| [CheckTrailingOrderShort](cexpertchecktrailingordershort.md) | Checks Trailing Stop conditions of Sell Limit/Stop order |
| [TrailingOrderLong](cexperttrailingorderlong.md) | Performs Trailing Stop for Buy Limit/Stop order |
| [TrailingOrderShort](cexperttrailingordershort.md) | Performs Trailing Stop for Sell Limit/Stop order |
| Order Delete Methods |  |
| [CheckDeleteOrderLong](cexpertcheckdeleteorderlong.md) | Checks conditions to delete Buy order |
| [CheckDeleteOrderShort](cexpertcheckdeleteordershort.md) | Checks conditions to delete Sell order |
| [DeleteOrders](cexpertdeleteorders.md) | Deletes all orders |
| [DeleteOrder](cexpertdeleteorder.md) | Deletes Stop/Limit order |
| [DeleteOrderLong](cexpertdeleteorderlong.md) | Deletes Buy Limit/Stop order |
| [DeleteOrderShort](cexpertdeleteordershort.md) | Deletes Sell Limit/Stop order |
| Trade Volume Methods |  |
| [LotOpenLong](cexpertlotopenlong.md) | Gets trade volume for buy operation |
| [LotOpenShort](cexpertlotopenshort.md) | Gets trade volume for sell operation |
| [LotReverse](cexpertlotreverse.md) | Gets trade volume for position reverse operation |
| Trade History Methods |  |
| [PrepareHistoryDate](cexpertpreparehistorydate.md) | Sets starting date for trade history tracking |
| [HistoryPoint](cexperthistorypoint.md) | Creates a checkpoint of trade history (saves number of positions, orders, deals and historical orders) |
| [CheckTradeState](cexpertchecktradestate.md) | Compares the current state with the saved one and calls the corresponding event handler |
| Event flags |  |
| [WaitEvent](cexpertwaitevent.md) | Sets the trading event waiting flag |
| [NoWaitEvent](cexpertnowaitevent.md) | Resets the trading event waiting flag |
| Trade Event Processing Methods |  |
| [TradeEventPositionStopTake](cexperttradeeventpositionstoptake.md) | Event handler of the "Position Stop Loss/Take Profit triggered" event |
| [TradeEventOrderTriggered](cexperttradeeventordertriggered.md) | Event handler of the "Pending Order Triggered" event |
| [TradeEventPositionOpened](cexperttradeeventpositionopened.md) | Event handler of the "Position Opened" event |
| [TradeEventPositionVolumeChanged](cexperttradeeventpositionvolumechanged.md) | Event handler of the "Position Volume Changed" event |
| [TradeEventPositionModified](cexperttradeeventpositionmodified.md) | Event handler of the "Position Modified" event |
| [TradeEventPositionClosed](cexperttradeeventpositionclosed.md) | Event handler of the "Position Closed" event |
| [TradeEventOrderPlaced](cexperttradeeventorderplaced.md) | Event handler of the "Pending Order Placed" event |
| [TradeEventOrderModified](cexperttradeeventordermodified.md) | Event handler of the "Pending Order Modified" event |
| [TradeEventOrderDeleted](cexperttradeeventorderdeleted.md) | Event handler of the "Pending Order Deleted" event |
| [TradeEventNotIdentified](cexperttradeeventnotidentified.md) | Event handler of the non-identified event |
| Service methods |  |
| [TimeframeAdd](cexperttimeframeadd.md) | Adds a timeframe to track |
| [TimeframesFlags](cexperttimeframesflags.md) | Forms timeframe flags |
| [SelectPosition](cexpertselectposition.md) | Selects a position to work with |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md) |