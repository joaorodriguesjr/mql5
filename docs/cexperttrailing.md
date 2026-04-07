CExpertTrailing



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md) / CExpertTrailing

[![Previous](previous.png)](cexpertsignaldirection.md) 
[![Next](next.png)](cexperttrailingchecktrailingstoplong.md)

CExpertTrailing

CExpertTrailing is a base class for trailing algorithms, it does nothing but provides the interfaces.

How to use it:

1. Prepare an algorithm for trailing;  
2. Create your own trailing class inherited from CExpertTrailing class;  
3. Override the virtual methods in your class with your own algorithms.

You can find an examples of trailing classes in the Expert\Trailing\ folder.

Description

CExpertTrailing is a base class for implementation of trailing stop algorithms.

Declaration

```
   class CExpertTrailing : public CExpertBase
```

Title

```
   #include <Expert\ExpertTrailing.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            CExpertTrailing  Direct descendants  [CTrailingFixedPips](ctrailingfixedpips.md), [CTrailingMA](ctrailingma.md), [CTrailingNone](ctrailingnone.md), [CTrailingPSAR](ctrailingpsar.md) |

Class Methods by Groups

| Checking of Trailing Stop Conditions |  |
| --- | --- |
| virtual [CheckTrailingStopLong](cexperttrailingchecktrailingstoplong.md) | Checks conditions to modify parameters of the long position |
| virtual [CheckTrailingStopShort](cexperttrailingchecktrailingstopshort.md) | Checks conditions to modify parameters of the short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [ValidationSettings](cexpertbasevalidationsettings.md), [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |