Technical Indicators



[MQL5 Reference](index.md) / Technical Indicators

[![Previous](previous.png)](textgetsize.md) 
[![Next](next.png)](iac.md)

Technical Indicator Functions

All functions like iMA, iAC, iMACD, iIchimoku etc. create a copy of the corresponding technical indicator in the global cache of the client terminal. If a copy of the indicator with such parameters already exists, the new copy is not created, and the counter of references to the existing copy increases.

These functions return the handle of the appropriate copy of the indicator. Further, using this handle, you can receive data calculated by the corresponding indicator. The corresponding buffer data (technical indicators contain calculated data in their internal buffers, which can vary from 1 to 5, depending on the indicator) can be copied to a mql5-program using the [CopyBuffer()](copybuffer.md) function.

You can't refer to the indicator data right after it has been created, because calculation of indicator values requires some time, so it's better to create indicator handles in OnInit(). Function [iCustom()](icustom.md) creates the corresponding custom indicator, and returns its handle in case it is successfully create. Custom indicators can contain up to 512 indicator buffers, the contents of which can also be obtained by the [CopyBuffer()](copybuffer.md) function, using the obtained handle.

There is a universal method for creating any technical indicator using the [IndicatorCreate()](indicatorcreate.md) function. This function accepts the following data as input parameters:

* symbol name;
* timeframe;
* type of the indicator to create;
* number of input parameters of the indicator;
* an array of [MqlParam](mqlparam.md) type containing all the necessary input parameters.

The computer memory can be freed from an indicator that is no more utilized, using the [IndicatorRelease()](indicatorrelease.md) function, to which the indicator handle is passed.

Note. Repeated call of the indicator function with the same parameters within one mql5-program does not lead to a multiple increase of the reference counter; the counter will be increased only once by 1. However, it's recommended to get the indicators handles in function [OnInit()](oninit.md) or in the class constructor, and further use these handles in other functions. The reference counter decreases when a mql5-program is deinitialized.

All indicator functions have at least 2 parameters - symbol and period. The [NULL](void.md) value of the symbol means the current symbol, the 0 value of the period means the current [timeframe](enum_timeframes.md).

| Function | Returns the handle of the indicator: |
| --- | --- |
| [iAC](iac.md) | Accelerator Oscillator |
| [iAD](iad.md) | Accumulation/Distribution |
| [iADX](iadx.md) | Average Directional Index |
| [iADXWilder](iadxwilder.md) | Average Directional Index by Welles Wilder |
| [iAlligator](ialligator.md) | Alligator |
| [iAMA](iama.md) | Adaptive Moving Average |
| [iAO](iao.md) | Awesome Oscillator |
| [iATR](iatr.md) | Average True Range |
| [iBearsPower](ibearspower.md) | Bears Power |
| [iBands](ibands.md) | Bollinger Bands® |
| [iBullsPower](ibullspower.md) | Bulls Power |
| [iCCI](icci.md) | Commodity Channel Index |
| [iChaikin](ichaikin.md) | Chaikin Oscillator |
| [iCustom](icustom.md) | Custom indicator |
| [iDEMA](idema.md) | Double Exponential Moving Average |
| [iDeMarker](idemarker.md) | DeMarker |
| [iEnvelopes](ienvelopes.md) | Envelopes |
| [iForce](iforce.md) | Force Index |
| [iFractals](ifractals.md) | Fractals |
| [iFrAMA](iframa.md) | Fractal Adaptive Moving Average |
| [iGator](igator.md) | Gator Oscillator |
| [iIchimoku](iichimoku.md) | Ichimoku Kinko Hyo |
| [iBWMFI](ibwmfi.md) | Market Facilitation Index by Bill Williams |
| [iMomentum](imomentum.md) | Momentum |
| [iMFI](imfi.md) | Money Flow Index |
| [iMA](ima.md) | Moving Average |
| [iOsMA](iosma.md) | Moving Average of Oscillator (MACD histogram) |
| [iMACD](imacd.md) | Moving Averages Convergence-Divergence |
| [iOBV](iobv.md) | On Balance Volume |
| [iSAR](isar.md) | Parabolic Stop And Reverse System |
| [iRSI](irsi.md) | Relative Strength Index |
| [iRVI](irvi.md) | Relative Vigor Index |
| [iStdDev](istddev.md) | Standard Deviation |
| [iStochastic](istochastic.md) | Stochastic Oscillator |
| [iTEMA](itema.md) | Triple Exponential Moving Average |
| [iTriX](itrix.md) | Triple Exponential Moving Averages Oscillator |
| [iWPR](iwpr.md) | Williams' Percent Range |
| [iVIDyA](ividya.md) | Variable Index Dynamic Average |
| [iVolumes](ivolumes.md) | Volumes |