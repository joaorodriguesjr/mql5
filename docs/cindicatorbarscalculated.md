BarsCalculated



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / BarsCalculated

[![Previous](previous.png)](cindicatorbufferresize.md) 
[![Next](next.png)](cindicatorgetdata.md)

BarsCalculated

Returns the amount of calculated data for the indicator.

```
int  BarsCalculated() const;
```

Return Value

Returns the amount of calculated data in the indicator buffer, or -1 in the case of error (data is not calculated yet).