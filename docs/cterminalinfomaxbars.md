MaxBars



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / MaxBars

[![Previous](previous.png)](cterminalinfoisftpenabled.md) 
[![Next](next.png)](cterminalinfocodepage.md)

MaxBars

Gets the maximum number of bars on chart specified in the terminal settings.

```
int  MaxBars() const
```

Return Value

Maximum number of bars on the chart.

Note

The maximum number of bars on chart is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_MAXBARS](terminalstatus.md#enum_terminal_info_integer) property).