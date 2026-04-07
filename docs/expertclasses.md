Strategy Modules



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md) / Strategy Modules

[![Previous](previous.png)](cterminalinfoinfostring.md) 
[![Next](next.png)](expertbaseclasses.md)

Classes for Creating and Testing Trading Strategies

This section contains technical details of working with classes for creation and testing of trading strategies and description of the relevant components of the MQL5 standard library.

The use of these classes will save time when creating (and especially testing) trading strategies.

MQL5 Standard Library (in terms of trading strategies) is placed in the terminal directory, in the Include\Expert folder.

| Base classes | Description |
| --- | --- |
| [CExpertBase](cexpertbase.md) | Base class for all trading strategy classes |
| [CExpert](cexpert.md) | Base class for Expert Advisor |
| [CExpertSignal](cexpertsignal.md) | Base class for Trading Signal classes |
| [CExpertTrailing](cexperttrailing.md) | Base class for Trailing Stop classes |
| [CExpertMoney](cexpertmoney.md) | Base class for Money Management classes |

| Trading signal classes | Description |
| --- | --- |
| [CSignalAC](signal_ac.md) | The module of signals based on market models of the indicator Accelerator Oscillator. |
| [CSignalAMA](signal_ama.md) | The module of signals based on market models of the indicator Adaptive Moving Average. |
| [CSignalAO](signal_ao.md) | The module of signals based on market models of the indicator Awesome Oscillator. |
| [CSignalBearsPower](signal_bears.md) | The module of signals based on market models of the oscillator Bears Power. |
| [CSignalBullsPower](signal_bulls.md) | The module of signals based on market models of the oscillator Bulls Power. |
| [CSignalCCI](signal_cci.md) | The module of signals based on market models of the oscillator Commodity Channel Index. |
| [CSignalDeM](signal_demarker.md) | The module of signals based on market models of the oscillator DeMarker. |
| [CSignalDEMA](signal_dema.md) | The module of signals based on market models of the indicator Double Exponential Moving Average. |
| [CSignalEnvelopes](signal_envelopes.md) | The module of signals based on market models of the indicator Envelopes. |
| [CSignalFrAMA](signal_frama.md) | The module of signals based on market models of the indicator Fractal Adaptive Moving Average. |
| [CSignalITF](signal_time_filter.md) | The module of filtration of signals by time. |
| [CSignalMACD](signal_macd.md) | The module of signals based on market models of the oscillator MACD. |
| [CSignalMA](signal_ma.md) | The module of signals based on market models of the indicator Moving Average. |
| [CSignalSAR](signal_sar.md) | The module of signals based on market models of the indicator Parabolic SAR. |
| [CSignalRSI](signal_rsi.md) | The module of signals based on market models of the oscillator Relative Strength Index. |
| [CSignalRVI](signal_rvi.md) | The module of signals based on market models of the oscillator Relative Vigor Index. |
| [CSignalStoch](signal_stochastic.md) | The module of signals based on market models of the oscillator Stochastic. |
| [CSignalTRIX](signal_trix.md) | The module of signals based on market models of the oscillator Triple Exponential Average. |
| [CSignalTEMA](signal_tema.md) | The module of signals based on market models of the indicator Triple Exponential Moving Average. |
| [CSignalWPR](signal_wpr.md) | The module of signals based on market models of the oscillator Williams Percent Range. |

| Trailing Stop classes | Description |
| --- | --- |
| [CTrailingFixedPips](ctrailingfixedpips.md) | This class implements Trailing Stop algorithm based on fixed points |
| [CTrailingMA](ctrailingma.md) | This class implements Trailing Stop algorithm based on the values of Moving Average indicator |
| [CTrailingNone](ctrailingnone.md) | A stub class, it does not use any Trailing Stop algorithm |
| [CTrailingPSAR](ctrailingpsar.md) | This class implements Trailing Stop algorithm based on the values of Parabolic SAR indicator |

| Money Management classes | Description |
| --- | --- |
| [CMoneyFixedLot](cmoneyfixedlot.md) | A class with an algorithm based on trading with predefined fixed lot size. |
| [CMoneyFixedMargin](cmoneyfixedmargin.md) | A class with an algorithm based on trading with predefined fixed margin. |
| [CMoneyFixedRisk](cmoneyfixedrisk.md) | A class with an algorithm based on trading with predefined risk. |
| [CMoneyNone](cmoneynone.md) | A class with an algorithm based on trading with minimal allowed lot size. |
| [CMoneySizeOptimized](cmoneysizeoptimized.md) | A class with an algorithm based on trading with variable lot size, depending on the results of the previous deals. |