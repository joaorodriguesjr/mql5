market\_book\_add



[MQL5 Reference](index.md)  /  [Python Integration](python_metatrader5.md) / market\_book\_add

[![Previous](previous.png)](mt5symbolselect_py.md) 
[![Next](next.png)](mt5marketbookget_py.md)

market\_book\_add

Subscribes the MetaTrader 5 terminal to the Market Depth change events for a specified symbol.

```
market_book_add(
   symbol      // financial instrument name
)
```

symbol

[in]  Financial instrument name. Required unnamed parameter.

Return Value

True if successful, otherwise False.

Note

The function is similar to [MarketBookAdd](marketbookadd.md).

 

See also

[market\_book\_get](mt5marketbookget_py.md), [market\_book\_release](mt5marketbookrelease_py.md), [Market Depth structure](mqlbookinfo.md)