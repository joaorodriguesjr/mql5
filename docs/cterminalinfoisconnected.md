IsConnected



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / IsConnected

[![Previous](previous.png)](cterminalinfobuild.md) 
[![Next](next.png)](cterminalinfoisdllsallowed.md)

IsConnected

Gets the information about connection to trade server.

```
bool  IsConnected() const
```

Return Value

true - the terminal is connected to a trade server, otherwise - false.

Note

Connection status is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_CONNECTED](terminalstatus.md#enum_terminal_info_integer) property).