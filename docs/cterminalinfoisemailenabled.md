IsEmailEnabled



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / IsEmailEnabled

[![Previous](previous.png)](cterminalinfoistradeallowed.md) 
[![Next](next.png)](cterminalinfoisftpenabled.md)

IsEmailEnabled

Gets the information about permission to send e-mails to SMTP server and login specified in the terminal settings.

```
bool  IsEmailEnabled() const
```

Return Value

true - sending e-mails is allowed, otherwise - false.

Note

Permission to send e-mails is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_EMAIL\_ENABLED](terminalstatus.md#enum_terminal_info_integer) property).