RefreshCurrent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicatorBuffer](cindicatorbuffer.md) / RefreshCurrent

[![Previous](previous.png)](cindicatorbufferrefresh.md) 
[![Next](next.png)](cseries.md)

RefreshCurrent

Updates the current (zeroth) buffer element.

```
bool  RefreshCurrent(
   const int  handle,     // handle of the indicator
   const int  num         // buffer number
   )
```

Parameters

handle

[in]  Handle of the indicator.

num

[in]  Indicator buffer number.

Return Value

true successful, false cannot update the buffer.