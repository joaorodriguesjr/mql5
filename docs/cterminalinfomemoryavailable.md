MemoryAvailable



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / MemoryAvailable

[![Previous](previous.png)](cterminalinfomemorytotal.md) 
[![Next](next.png)](cterminalinfomemoryused.md)

MemoryAvailable

Gets the information about the free memory available to the client terminal/agent (in Mb).

```
int  MemoryTotal() const
```

Return Value

Free memory (in Mb) available to the terminal/agent.

Note

The free memory available to the client terminal/agent is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_MEMORY\_TOTAL](terminalstatus.md#enum_terminal_info_integer) property).