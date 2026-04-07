Use of a Codepage



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Input/Output Constants](io_constants.md) / Use of a Codepage

[![Previous](previous.png)](enum_file_position.md) 
[![Next](next.png)](messbconstants.md)

Using a Codepage in String Conversion Operations

When converting [string](stringconst.md) variables into arrays of [char type](integertypes.md#char) and back, the encoding that by default corresponds to the current ANSI of Windows operating system (CP\_ACP) is used in MQL5. If you want to specify a different type of encoding, it can be set as additional parameter for the [CharArrayToString()](chararraytostring.md), [StringToCharArray()](stringtochararray.md) and [FileOpen()](fileopen.md) functions.

The table lists the built-in constants for some of the most popular code pages. Not mentioned code pages can be specified by a code corresponding to the page.

Built-in Constants of Codepages

| Constant | Value | Description |
| --- | --- | --- |
| CP\_ACP | 0 | The current Windows ANSI code page. |
| CP\_OEMCP | 1 | The current system OEM code page. |
| CP\_MACCP | 2 | The current system Macintosh code page.  Note: This value is mostly used in earlier created program codes and is of no use now, since modern Macintosh computers use Unicode for encoding. |
| CP\_THREAD\_ACP | 3 | The Windows ANSI code page for the current thread. |
| CP\_SYMBOL | 42 | Symbol code page |
| CP\_UTF7 | 65000 | UTF-7 code page. |
| CP\_UTF8 | 65001 | UTF-8 code page. |

See also

[Client Terminal Properties](terminalstatus.md#enum_terminal_info_integer)