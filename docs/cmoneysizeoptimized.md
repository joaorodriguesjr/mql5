CMoneySizeOptimized



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md) / CMoneySizeOptimized

[![Previous](previous.png)](cmoneynonecheckopenshort.md) 
[![Next](next.png)](cmoneysizeoptimizeddecreasefactor.md)

CMoneySizeOptimized

CMoneySizeOptimized is a class with implementation of money and risk management algorithm depending on results of the previous deals.

Description

CMoneySizeOptimized implements the market entry algorithm with the lot size depending on results of the previous deals.

Declaration

```
   class CMoneySizeOptimized: public CExpertMoney
```

Title

```
   #include <Expert\Money\MoneySizeOptimized.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertMoney](cexpertmoney.md)                CMoneySizeOptimized |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| [DecreaseFactor](cmoneysizeoptimizeddecreasefactor.md) | Sets the parameter value |
| virtual [ValidationSettings](cmoneysizeoptimizedvalidationsettings.md) | Checks the settings |
| Money and Risk Management Methods |  |
| virtual [CheckOpenLong](cmoneysizeoptimizedcheckopenlong.md) | Gets trade volume for a long position |
| virtual [CheckOpenShort](cmoneysizeoptimizedcheckopenshort.md) | Gets trade volume for a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |
| Methods inherited from class CExpertMoney  [Percent](cexpertmoneypercent.md), [CheckReverse](cexpertmoneycheckreverse.md), [CheckClose](cexpertmoneycheckclose.md) |