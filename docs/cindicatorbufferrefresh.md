Refresh



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicatorBuffer](cindicatorbuffer.md) / Refresh

[![Previous](previous.png)](cindicatorbufferat.md) 
[![Next](next.png)](cindicatorbufferrefreshcurrent.md)

Refresh

Updates the whole buffer.

```
bool  Refresh(
   const int  handle,     // indicator handle
   const int  num         // buffer number
   )
```

Parameters

handle

[in]  Handle of the indicator.

num

[in]  Buffer index of the indicator.

Return Value

true successful, false cannot update the buffer.