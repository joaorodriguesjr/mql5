CMoneyFixedMargin



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md) / CMoneyFixedMargin

[![Previous](previous.png)](cmoneyfixedlotcheckopenshort.md) 
[![Next](next.png)](moneyfixedmargincheckopenlong.md)

CMoneyFixedMargin

CMoneyFixedMargin is the class designed to implement money management algorithm based on trading with predefined fixed margin.

Description

CMoneyFixedMargin implements money management algorithm based on trading with predefined fixed margin.

Declaration

```
   class CMoneyFixedMargin: public CExpertMoney
```

Title

```
   #include <Expert\Money\MoneyFixedMargin.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CExpertBase](cexpertbase.md)            [CExpertMoney](cexpertmoney.md)                CMoneyFixedMargin |

Class Methods by Groups

| Money and Risk Management Methods |  |
| --- | --- |
| virtual [CheckOpenLong](moneyfixedmargincheckopenlong.md) | Gets trade volume for a long position |
| virtual [CheckOpenShort](moneyfixedmargincheckopenshort.md) | Gets trade volume for a short position |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CExpertBase  [InitPhase](cexpertbaseinitphase.md), [TrendType](cexpertbasetrendtype.md), [UsedSeries](cexpertbaseusedseries.md), [EveryTick](cexpertbaseeverytick.md), [Open](cexpertbaseopen.md), [High](cexpertbasehigh.md), [Low](cexpertbaselow.md), [Close](cexpertbaseclose.md), [Spread](cexpertbasespread.md), [Time](cexpertbasetime.md), [TickVolume](cexpertbasetickvolume.md), [RealVolume](cexpertbaserealvolume.md), [Init](cexpertbaseinit.md), [Symbol](cexpertbasesymbol.md), [Period](cexpertbaseperiod.md), [Magic](cexpertbasemagic.md), SetMarginMode, [SetPriceSeries](cexpertbasesetpriceseries.md), [SetOtherSeries](cexpertbasesetotherseries.md), [InitIndicators](cexpertbaseinitindicators.md) |
| Methods inherited from class CExpertMoney  [Percent](cexpertmoneypercent.md), [ValidationSettings](cexpertmoneyvalidationsettings.md), [CheckReverse](cexpertmoneycheckreverse.md), [CheckClose](cexpertmoneycheckclose.md) |