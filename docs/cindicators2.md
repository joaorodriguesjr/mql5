CIndicators



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CIndicators

[![Previous](previous.png)](cindicatordeletefromchart.md) 
[![Next](next.png)](cindicatorscreate.md)

CIndicators

The CIndicators is a class for collecting instances of timeseries and technical indicators classes.

Description

CIndicators class provides creation of the technical indicators class instances, their storage and management (data synchronization, handle and memory management).

Declaration

```
   class CIndicators: public CArrayObj
```

Title

```
   #include <Indicators\Indicators.mqh>
```

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cindicatorscreate.md) | Creates an indicator |
| Data Update |  |
| [Refresh](cindicatorsrefresh.md) | Updates indicator data |