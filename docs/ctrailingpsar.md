CTrailingPSAR



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md) / CTrailingPSAR

[![Previous](previous.png)](ctrailingnonechecktrailingstopshort.md) 
[![Next](next.png)](trailingparabolicsarstep.md)

CTrailingPSAR

CTrailingPSAR is a class with implementation of Trailing Stop algorithm based on the values of Parabolic SAR indicator.

Description

CTrailingPSAR class implements the Trailing Stop algorithm based on the values of Parabolic SAR indicator of the previous (completed) bar.

Declaration

```
class CTrailingPSAR: public CExpertTrailing
```

Title

```
   #include <Expert\Trailing\TrailingParabolicSAR.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertTrailing](cexperttrailing.md)                CTrailingPSAR |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| [Step](trailingparabolicsarstep.md) | Sets the value of step of Parabolic SAR indicator |
| [Maximum](trailingparabolicsarmaximum.md) | Sets the value of maximum of Parabolic SAR indicator |
| virtual [InitIndicators](trailingparabolicsarinitindicators.md) | Initializes indicators and timeseries |
| Check Trailing Methods |  |
| virtual [CheckTrailingStopLong](trailingparabolicsarchecktrailingstoplong.md) | Check conditions of trailing stop of a long position |
| virtual [CheckTrailingStopShort](trailingparabolicsarchecktrailingstopshort.md) | Check conditions of trailing stop of a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [ValidationSettings](cexpertbasevalidationsettings.md), [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md) |