CMoneyNone



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md) / CMoneyNone

[![Previous](previous.png)](cmoneyfixedriskcheckopenshort.md) 
[![Next](next.png)](cmoneynonevalidationsettings.md)

CMoneyNone

CMoneyNone is a class with implementation of the "absence" of money and risk management.

Description

CMoneyNone class implements trading with minimal allowed lot.

Declaration

```
   class CMoneyNone: public CExpertMoney
```

Title

```
   #include <Expert\Money\MoneyNone.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertMoney](cexpertmoney.md)                CMoneyNone |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| virtual [ValidationSettings](cmoneynonevalidationsettings.md) | Checks the settings |
| Money and Risk Management Methods |  |
| virtual [CheckOpenLong](cmoneynonecheckopenlong.md) | Gets trade volume for a long position |
| virtual [CheckOpenShort](cmoneynonecheckopenshort.md) | Gets trade volume for a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |
| Methods inherited from class CExpertMoney  [Percent](cexpertmoneypercent.md), [CheckReverse](cexpertmoneycheckreverse.md), [CheckClose](cexpertmoneycheckclose.md) |