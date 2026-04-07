CExpertSignal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md) / CExpertSignal

[![Previous](previous.png)](cexperttimeframesflags.md) 
[![Next](next.png)](cexpertsignalbaseprice.md)

CExpertSignal

CExpertSignal is a base class for trading signals, it does nothing (except [CheckReverseLong()](cexpertsignalcheckreverselong.md) and [CheckReverseShort()](cexpertsignalcheckreverseshort.md) methods) but provides the interfaces.

How to use it:

1. Prepare an algorithm for trading signals;  
2. Create your own trading signal class, inherited from CExpertSignal class;  
3. Override the virtual methods in your class with your own algorithms.

You can find an examples of trading signal classes in the Expert\Signal\ folder.

Description

CExpertSignal is a base class for implementation of trading signal algorithms.

Declaration

```
   class CExpertSignal : public CExpertBase
```

Title

```
   #include <Expert\ExpertSignal.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            CExpertSignal  Direct descendants  CSignalAC, CSignalAMA, CSignalAO, CSignalBearsPower, CSignalBullsPower, CSignalCCI, CSignalDeM, CSignalDEMA, CSignalEnvelopes, CSignalFrAMA, CSignalRSI, CSignalRVI, CSignalSAR, CSignalStoch, CSignalTEMA, CSignalTriX, CSignalWPR |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| virtual [InitIndicators](cexpertsignalinitindicators.md) | Initializes indicators and timeseries |
| virtual [ValidationSettings](cexpertsignalvalidationsettings.md) | Checks the object settings |
| virtual [AddFilter](cexpertsignaladdfilter.md) | Adds a filter to combined signal |
| Access to Protected Data |  |
| [BasePrice](cexpertsignalbaseprice.md) | Sets base price level |
| [UsedSeries](cexpertsignalusedseries.md) | Gets the flags of timeseries used |
| Parameters Setting |  |
| [Weight](cexpertsignalweight.md) | Sets the value of "Weight" parameter |
| [PatternsUsage](cexpertsignalpatternsusage.md) | Sets the value of "PatternsUsage" parameter |
| [General](cexpertsignalgeneral.md) | Sets the value of "General" parameter |
| [Ignore](cexpertsignalignore.md) | Sets the value of "Ignore" parameter |
| [Invert](cexpertsignalinvert.md) | Sets the value of "Invert" parameter |
| [ThresholdOpen](cexpertsignalthresholdopen.md) | Sets the value of "ThresholdOpen" parameter |
| [ThresholdClose](cexpertsignalthresholdclose.md) | Sets the value of "ThresholdClose" parameter |
| [PriceLevel](cexpertsignalpricelevel.md) | Sets the value of "PriceLevel" parameter |
| [StopLevel](cexpertsignalstoplevel.md) | Sets the value of "StopLevel" parameter |
| [TakeLevel](cexpertsignaltakelevel.md) | Sets the value of "TakeLevel" parameter |
| [Expiration](cexpertsignalexpiration.md) | Sets the value of "Expiration" parameter |
| [Magic](cexpertsignalmagic.md) | Sets the value of "Magic" parameter |
| Checking Trading Conditions |  |
| virtual [CheckOpenLong](cexpertsignalcheckopenlong.md) | Checks conditions to open long position |
| virtual [CheckCloseLong](cexpertsignalcheckcloselong.md) | Checks conditions to close long position |
| virtual [CheckOpenShort](cexpertsignalcheckopenshort.md) | Checks conditions to open short position |
| virtual [CheckCloseShort](cexpertsignalcheckcloseshort.md) | Checks conditions to close short position |
| virtual [CheckReverseLong](cexpertsignalcheckreverselong.md) | Checks conditions of long position reversal |
| virtual [CheckReverseShort](cexpertsignalcheckreverseshort.md) | Checks conditions of short position reversal |
| Trade Parameters Setting |  |
| virtual [OpenLongParams](cexpertsignalopenlongparams.md) | Sets parameters for long position opening |
| virtual [OpenShortParams](cexpertsignalopenshortparams.md) | Sets parameters for short position opening |
| virtual [CloseLongParams](cexpertsignalcloselongparams.md) | Sets parameters for long position closing |
| virtual [CloseShortParams](cexpertsignalcloseshortparams.md) | Sets parameters for short position closing |
| Checking of Order Trailing Conditions |  |
| virtual [CheckTrailingOrderLong](cexpertsignalchecktrailingorderlong.md) | Checks conditions to modify parameters of Buy Pending order |
| virtual [CheckTrailingOrderShort](cexpertsignalchecktrailingordershort.md) | Checks conditions to modify parameters of Sell Pending order |
| Methods to Check Formation of Market Orders |  |
| virtual [LongCondition](cexpertsignallongcondition.md) | Gets the result of checking buy conditions |
| virtual [ShortCondition](cexpertsignalshortcondition.md) | Gets the result of checking sell conditions |
| virtual [Direction](cexpertsignaldirection.md) | Gets the "weighted" direction of price |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md) |