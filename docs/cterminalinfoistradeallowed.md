IsTradeAllowed



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / IsTradeAllowed

[![Previous](previous.png)](cterminalinfoisdllsallowed.md) 
[![Next](next.png)](cterminalinfoisemailenabled.md)

IsTradeAllowed

Gets the information about permission to trade.

```
bool  IsTradeAllowed() const
```

Return Value

true - trade allowed, otherwise - false.

Note

Permission to trade is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_TRADE\_ALLOWED](terminalstatus.md#enum_terminal_info_integer) property).