MemoryUsed



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / MemoryUsed

[![Previous](previous.png)](cterminalinfomemoryavailable.md) 
[![Next](next.png)](cterminalinfoisx64.md)

MemoryUsed

Gets the information about the memory used by the client terminal/agent (in Mb).

```
int  MemoryUsed() const
```

Return Value

The memory used by the client terminal/agent (in Mb).

Note

The memory used by the client terminal/agent is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_MEMORY\_USED](terminalstatus.md#enum_terminal_info_integer) property).