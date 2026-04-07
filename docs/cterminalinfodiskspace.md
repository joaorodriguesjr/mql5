DiskSpace



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / DiskSpace

[![Previous](previous.png)](cterminalinfoopenclsupport.md) 
[![Next](next.png)](cterminalinfolanguage.md)

DiskSpace

Gets the information about free disk space available for MQL5\Files folder of the terminal/agent (in Mb).

```
int  MDiskSpace() const
```

Return Value

Free disk space.

Note

Free disk space is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_DISK\_SPACE](terminalstatus.md#enum_terminal_info_integer) property).