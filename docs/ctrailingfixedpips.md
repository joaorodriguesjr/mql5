CTrailingFixedPips



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md) / CTrailingFixedPips

[![Previous](previous.png)](sampletrailingclasses.md) 
[![Next](next.png)](ctrailingfixedpipsstoplevel.md)

CTrailingFixedPips

CTrailingFixedPips is a class with implementation of Trailing Stop algorithm based on fixed points trailing.

CTrailingFixedPips class implements the following algorithm of trailing open positions: If Stop Loss level is equal to zero, Stop Loss order modification condition is considered unfulfilled, therefore there is no suggestion to change a position's Stop Loss. Otherwise, the check of whether the price has moved in favorable direction is performed.

If a position has a Stop Loss order, it checks the minimal allowed Stop Loss distance to the current price. If the position has no Stop Loss level, the distance between the current and open prices is checked. If the distance exceeds Stop Loss level, the system suggests to set a new Stop Loss price.

If Stop Loss modification condition is fulfilled and Take Profit is not equal to zero, the system suggests setting a new Take Profit price.

If Expert Advisor class has been [initialized](cexpertinit.md) with the flag every\_tick=false, it will perform all operations (trading, trailing, etc) only at the new bar on a working symbol and timeframe. In this case, setting Take Profit order allows you to close position when the price moves in the position direction before a new bar appears.

Description

CTrailingFixedPips implements the Trailing Stop algorithm at a specified "distance" from the current price (in points).

Declaration

```
class CTrailingFixedPips: public CExpertTrailing
```

Title

```
   #include <Expert\Trailing\CTrailingFixedPips.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertTrailing](cexperttrailing.md)                CTrailingFixedPips |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| [StopLevel](ctrailingfixedpipsstoplevel.md) | Sets the value of Stop Loss level |
| [ProfitLevel](ctrailingfixedpipsprofitlevel.md) | Sets the value of Take Profit level |
| virtual [ValidationSettings](ctrailingfixedpipsvalidationsettings.md) | Checks the settings |
| Check Trailing Methods |  |
| virtual [CheckTrailingStopLong](ctrailingfixedpipschecktrailingstoplong.md) | Check Trailing Stop conditions of a long position |
| virtual [CheckTrailingStopShort](ctrailingfixedpipschecktrailingstopshort.md) | Check Trailing Stop conditions of a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |