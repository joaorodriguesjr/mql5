MemoryTotal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / MemoryTotal

[![Previous](previous.png)](cterminalinfomemoryphysical.md) 
[![Next](next.png)](cterminalinfomemoryavailable.md)

MemoryTotal

Gets the information about the total memory available to the terminal/agent (in Mb).

```
int  MemoryTotal() const
```

Return Value

Total memory (in Mb) available to the terminal/agent.

Note

The total memory available to the terminal/agent is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_MEMORY\_TOTAL](terminalstatus.md#enum_terminal_info_integer) property).