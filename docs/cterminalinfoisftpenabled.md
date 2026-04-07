IsFtpEnabled



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / IsFtpEnabled

[![Previous](previous.png)](cterminalinfoisemailenabled.md) 
[![Next](next.png)](cterminalinfomaxbars.md)

IsFtpEnabled

Gets the information about permission to send trade reports to FTP server and login specified in the terminal settings.

```
bool  IsFtpEnabled() const
```

Return Value

true - sending trade reports to FTP server is allowed, otherwise - false.

Note

Permission to send trade reports is defined [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_FTP\_ENABLED](terminalstatus.md#enum_terminal_info_integer) property).