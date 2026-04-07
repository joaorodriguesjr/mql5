Indicators Lines



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Indicator Constants](indicatorconstants.md) / Indicators Lines

[![Previous](previous.png)](enum_ma_method.md) 
[![Next](next.png)](drawstyles.md)

Indicators Lines

Some [technical indicators](indicators.md) have several buffers drawn in the chart. Numbering of indicator buffers starts with 0. When copying indicator values using the [CopyBuffer()](copybuffer.md) function into an array of the double type, for some indicators one may indicate the identifier of a copied buffer instead of its number.

 

Identifiers of indicator lines permissible when copying values of [iMACD()](imacd.md), [iRVI()](irvi.md) and [iStochastic()](istochastic.md).

| Constant | Value | Description |
| --- | --- | --- |
| MAIN\_LINE | 0 | Main line |
| SIGNAL\_LINE | 1 | Signal line |

Identifiers of indicator lines permissible when copying values of [ADX()](iadx.md) and [ADXW()](iadxwilder.md).

| Constant | Value | Description |
| --- | --- | --- |
| MAIN\_LINE | 0 | Main line |
| PLUSDI\_LINE | 1 | Line +DI |
| MINUSDI\_LINE | 2 | Line DI |

Identifiers of indicator lines permissible when copying values of [iBands()](ibands.md).

| Constant | Value | Description |
| --- | --- | --- |
| BASE\_LINE | 0 | Main line |
| UPPER\_BAND | 1 | Upper limit |
| LOWER\_BAND | 2 | Lower limit |

Identifiers of indicator lines permissible when copying values of [iEnvelopes()](ienvelopes.md) and [iFractals()](ifractals.md).

| Constant | Value | Description |
| --- | --- | --- |
| UPPER\_LINE | 0 | Upper line |
| LOWER\_LINE | 1 | Bottom line |

Identifiers of indicator lines permissible when copying values of [iGator()](igator.md)

| Constant | Value | Description |
| --- | --- | --- |
| UPPER\_HISTOGRAM | 0 | Upper histogram |
| LOWER\_HISTOGRAM | 2 | Bottom histogram |

Identifiers of indicator lines permissible when copying values of [iAlligator()](ialligator.md).

| Constant | Value | Description |
| --- | --- | --- |
| GATORJAW\_LINE | 0 | Jaw line |
| GATORTEETH\_LINE | 1 | Teeth line |
| GATORLIPS\_LINE | 2 | Lips line |

Identifiers of indicator lines permissible when copying values of [iIchimoku()](iichimoku.md).

| Constant | Value | Description |
| --- | --- | --- |
| TENKANSEN\_LINE | 0 | Tenkan-sen line |
| KIJUNSEN\_LINE | 1 | Kijun-sen line |
| SENKOUSPANA\_LINE | 2 | Senkou Span A line |
| SENKOUSPANB\_LINE | 3 | Senkou Span B line |
| CHIKOUSPAN\_LINE | 4 | Chikou Span line |