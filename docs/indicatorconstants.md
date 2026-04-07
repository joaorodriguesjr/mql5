Indicators constants 



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md) / Indicator Constants

[![Previous](previous.png)](wingdings.md) 
[![Next](next.png)](prices.md)

Indicators Constants

There are 37 predefined [technical indicators](indicators.md), which can be used in programs written in the MQL5 language. In addition, there is an opportunity to create custom indicators using the [iCustom()](icustom.md) function. All constants required for that are divided into 5 groups:

* [Price constants](prices.md) for selecting the type of price or volume, on which an indicator is calculated;
* [Smoothing methods](enum_ma_method.md) built-in smoothing methods used in indicators;
* [Indicator lines](lines.md) identifiers of indicator buffers when accessing indicator values using [CopyBuffer()](copybuffer.md);
* [Drawing styles](drawstyles.md) for indicating one of 18 types of drawing and setting the line drawing style;
* [Custom indicators properties](customindicatorproperties.md) are used in functions for working with [custom](customind.md) indicators;
* [Types of indicators](enum_indicator.md) are used for specifying the type of technical indicator when creating a handle using [IndicatorCreate()](indicatorcreate.md);
* [Identifiers of data types](enum_datatype.md) are used for specifying the type of data passed in an array of the [MqlParam](mqlparam.md) type into the [IndicatorCreate()](indicatorcreate.md) function.