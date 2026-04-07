market\_book\_release



[MQL5 Reference](index.md)  /  [Python Integration](python_metatrader5.md) / market\_book\_release

[![Previous](previous.png)](mt5marketbookget_py.md) 
[![Next](next.png)](mt5copyratesfrom_py.md)

market\_book\_release

Cancels subscription of the MetaTrader 5 terminal to the Market Depth change events for a specified symbol.

```
market_book_release(
   symbol      // financial instrument name
)
```

symbol

[in]  Financial instrument name. Required unnamed parameter.

Return Value

True if successful, otherwise False.

Note

The function is similar to [MarketBookRelease](marketbookrelease.md).

 

See also

[market\_book\_add](mt5marketbookadd_py.md), [market\_book\_get](mt5marketbookget_py.md), [Market Depth structure](mqlbookinfo.md)