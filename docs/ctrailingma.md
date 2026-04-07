CTrailingMA



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md) / CTrailingMA

[![Previous](previous.png)](ctrailingfixedpipschecktrailingstopshort.md) 
[![Next](next.png)](ctrailingmaperiod.md)

CTrailingMA

CTrailingMA is a class with implementation of Trailing Stop algorithm based on the values of moving average indicator.

Description

CTrailingMA class implements Trailing Stop algorithm based on the values of moving average indicator of the previous (completed) bar.

Declaration

```
class CTrailingMA: public CExpertTrailing
```

Title

```
   #include <Expert\Trailing\TrailingMA.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertTrailing](cexperttrailing.md)                CTrailingMA |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| [Period](ctrailingmaperiod.md) | Sets period of moving average |
| [Shift](ctrailingmashift.md) | Sets shift of moving average |
| [Method](ctrailingmamethod.md) | Sets smoothing method of moving average |
| [Applied](ctrailingmaapplied.md) | Sets applied price of moving average |
| virtual [InitIndicators](ctrailingmainitindicators.md) | Initializes indicators and timeseries |
| virtual [ValidationSettings](ctrailingmavalidationsettings.md) | Checks the settings |
| Check Trailing Methods |  |
| virtual [CheckTrailingStopLong](ctrailingmachecktrailingstoplong.md) | Check Trailing Stop conditions of a long position |
| virtual [CheckTrailingStopShort](ctrailingmachecktrailingstopshort.md) | Check Trailing Stop conditions of a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md) |