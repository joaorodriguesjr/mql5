CExpertMoney



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md) / CExpertMoney

[![Previous](previous.png)](cexperttrailingchecktrailingstopshort.md) 
[![Next](next.png)](cexpertmoneypercent.md)

CExpertMoney

CExpertMoney is a base class for money and risk management algorithms.

Description

CExpertMoney is a base class for implementation of money and risk management classes.

Declaration

```
   class CExpertMoney : public CObject
```

Title

```
   #include <Expert\ExpertMoney.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            CExpertMoney  Direct descendants  [CMoneyFixedLot](cmoneyfixedlot.md), [CMoneyFixedMargin](cmoneyfixedmargin.md), [CMoneyFixedRisk](cmoneyfixedrisk.md), [CMoneyNone](cmoneynone.md), [CMoneySizeOptimized](cmoneysizeoptimized.md) |

Class Methods by Groups

| Access to Protected Data |  |
| --- | --- |
| [Percent](cexpertmoneypercent.md) | Sets the value of "Risk percent" parameter |
| Initialization |  |
| virtual [ValidationSettings](cexpertmoneyvalidationsettings.md) | Checks the settings |
| Checking Trading Conditions |  |
| virtual [CheckOpenLong](cexpertmoneycheckopenlong.md) | Gets the volume for a long position |
| virtual [CheckOpenShort](cexpertmoneycheckopenshort.md) | Gets the volume for a short position |
| virtual [CheckReverse](cexpertmoneycheckreverse.md) | Gets the volume for a reverse of the position |
| virtual [CheckClose](cexpertmoneycheckclose.md) | Checks conditions to close an opened position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |