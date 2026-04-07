OpenCLSupport



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / OpenCLSupport

[![Previous](previous.png)](cterminalinfoisx64.md) 
[![Next](next.png)](cterminalinfodiskspace.md)

OpenCLSupport

Gets the information about the version of OpenCL supported by video card.

```
int  OpenCLSupport() const
```

Return Value

OpenCL version having the following form: 0x00010002 = "1.2". 0 means that OpenCL is not supported.

Note

OpenCL version is defined by [TerminalInfoInteger()](terminalinfointeger.md) function ([TERMINAL\_OPENCL\_SUPPORT](terminalstatus.md#enum_terminal_info_integer) property).