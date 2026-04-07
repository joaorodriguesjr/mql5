CExpertBase



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md) / CExpertBase

[![Previous](previous.png)](expertbaseclasses.md) 
[![Next](next.png)](cexpertbaseinitphase.md)

CExpertBase

CExpertBase is a base class for the [CExpert](cexpert.md) class and all auxiliary trading strategy classes.

Description

CExpertBase provides the data and methods, which are common to all objects of the Expert Advisor.

Declaration

```
   class CExpertBase : public CObject
```

Title

```
   #include <Expert\ExpertBase.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CExpertBase  Direct descendants  [CExpert](cexpert.md), [CExpertMoney](cexpertmoney.md), [CExpertSignal](cexpertsignal.md), [CExpertTrailing](cexperttrailing.md) |

Class Methods by Groups

Public Methods:

| Initialization |  |
| --- | --- |
| virtual [Init](cexpertbaseinit.md) | Initializes the object |
| virtual [ValidationSettings](cexpertbasevalidationsettings.md) | Checks the settings |
| Parameters |  |
| [Symbol](cexpertbasesymbol.md) | Sets the symbol |
| [Period](cexpertbaseperiod.md) | Sets the timeframe |
| [Magic](cexpertbasemagic.md) | Sets the Expert Advisor ID |
| Indicators and Timeseries |  |
| virtual [SetPriceSeries](cexpertbasesetpriceseries.md) | Sets pointers to external timeseries (price series) |
| virtual [SetOtherSeries](cexpertbasesetotherseries.md) | Sets pointers to external timeseries (non-price series) |
| virtual [InitIndicators](cexpertbaseinitindicators.md) | Initializes the indicators and timeseries |
| Access to Protected Data |  |
| [InitPhase](cexpertbaseinitphase.md) | Gets the current phase of object initialization |
| [TrendType](cexpertbasetrendtype.md) | Sets trend type |
| [UsedSeries](cexpertbaseusedseries.md) | Gets bitmask of timeseries used |
| [EveryTick](cexpertbaseeverytick.md) | Sets the "Every tick" flag |
| Access to Timeseries |  |
| [Open](cexpertbaseopen.md) | Gets the element of the Open timeseries by index |
| [High](cexpertbasehigh.md) | Gets the element of the High timeseries by index |
| [Low](cexpertbaselow.md) | Gets the element of the Low timeseries by index |
| [Close](cexpertbaseclose.md) | Gets the element of the Close timeseries by index |
| [Spread](cexpertbasespread.md) | Gets the element of the Spread timeseries by index |
| [Time](cexpertbasetime.md) | Gets the element of the Time timeseries by index |
| [TickVolume](cexpertbasetickvolume.md) | Gets the element of the TickVolume timeseries by index |
| [RealVolume](cexpertbaserealvolume.md) | Gets the element of the RealVolume timeseries by index |

Protected Methods:

| Initialization of Timeseries |  |
| --- | --- |
| [InitOpen](cexpertbaseinitopen.md) | Open timeseries initialization method |
| [InitHigh](cexpertbaseinithigh.md) | High timeseries initialization method |
| [InitLow](cexpertbaseinitlow.md) | Low timeseries initialization method |
| [InitClose](cexpertbaseinitclose.md) | Close timeseries initialization method |
| [InitSpread](cexpertbaseinitspread.md) | Spread timeseries initialization method |
| [InitTime](cexpertbaseinittime.md) | Time timeseries initialization method |
| [InitTickVolume](cexpertbaseinittickvolume.md) | TickVolume timeseries initialization method |
| [InitRealVolume](cexpertbaseinitrealvolume.md) | RealVolume timeseries initialization method |
| Service Methods |  |
| virtual [PriceLevelUnit](cexpertbasepricelevelunit.md) | Gets the price level unit |
| virtual [StartIndex](cexpertbasestartindex.md) | Gets the index of starting bar to analyze |
| virtual [CompareMagic](cexpertbasecomparemagic.md) | Compares the Expert Advisor ID with the specified value |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |