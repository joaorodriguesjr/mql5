CTrailingNone



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Trailing Stop Classes](sampletrailingclasses.md) / CTrailingNone

[![Previous](previous.png)](ctrailingmachecktrailingstopshort.md) 
[![Next](next.png)](ctrailingnonechecktrailingstoplong.md)

CTrailingNone

CTrailingNone is a stub class. This class should be used at initialization of trailing object in CExpert class if your strategy does not use Trailing Stop.

Description

CTrailingNone class does not implement any Trailing Stop algorithm. The methods of checking Trailing Stop conditions always return false.

Declaration

```
class CTrailingNone: public CExpertTrailing
```

Title

```
   #include <Expert\Trailing\TrailingNone.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertTrailing](cexperttrailing.md)                CTrailingNone |

Class Methods by Groups

| Check Trailing Methods |  |
| --- | --- |
| virtual [CheckTrailingStopLong](ctrailingnonechecktrailingstoplong.md) | A stub method for checking Trailing Stop conditions of a long position |
| virtual [CheckTrailingStopShort](ctrailingnonechecktrailingstopshort.md) | A stub method for checking Trailing Stop conditions of a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [ValidationSettings](cexpertbasevalidationsettings.md), [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |
| Methods inherited from class CExpertTrailing  [CheckTrailingStopLong](cexperttrailingchecktrailingstoplong.md), [CheckTrailingStopShort](cexperttrailingchecktrailingstopshort.md) |