IsX64



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / IsX64

[![Previous](previous.png)](cterminalinfomemoryused.md) 
[![Next](next.png)](cterminalinfoopenclsupport.md)

IsX64

Gets the information about the type of the client terminal.

```
bool  IsX64() const
```

Return Value

true - 64-bit version is used, otherwise - false.

Note

The type of the terminal is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_X64](terminalstatus.md#enum_terminal_info_integer) property).