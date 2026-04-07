CMoneyFixedLot



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md) / CMoneyFixedLot

[![Previous](previous.png)](samplemmclasses.md) 
[![Next](next.png)](cmoneyfixedlotlots.md)

CMoneyFixedLot

CMoneyFixedLot is the class designed to implement money management algorithm based on trading with predefined fixed lot size.

Description

CMoneyFixedLot implements money management algorithm based on trading with predefined fixed lot size.

Declaration

```
   class CMoneyFixedLot: public CExpertMoney
```

Title

```
   #include <Expert\Money\MoneyFixedLot.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertMoney](cexpertmoney.md)                CMoneyFixedLot |

Class Methods by Groups

| Initialization |  |
| --- | --- |
| [Lots](cmoneyfixedlotlots.md) | Sets trading volume |
| virtual [ValidationSettings](cmoneyfixedlotvalidationsettings.md) | Checks the settings |
| Money and Risk Management Methods |  |
| virtual [CheckOpenLong](cmoneyfixedlotcheckopenlong.md) | Gets trade volume for a long position |
| virtual [CheckOpenShort](cmoneyfixedlotcheckopenshort.md) | Gets trade volume for a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |
| Methods inherited from class CExpertMoney  [Percent](cexpertmoneypercent.md), [CheckReverse](cexpertmoneycheckreverse.md), [CheckClose](cexpertmoneycheckclose.md) |