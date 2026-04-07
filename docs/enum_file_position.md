In-File Position



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Input/Output Constants](io_constants.md) / In-File Position

[![Previous](previous.png)](enum_file_property_integer.md) 
[![Next](next.png)](codepageusage.md)

Positioning Inside a File

Most of [file functions](files.md) are associated with data read/write operations. At the same time, using the [FileSeek()](fileseek.md) you can specify the position of a file pointer to a position inside the file, from which the next read or write operation will be performed. The ENUM\_FILE\_POSITION enumeration contains valid pointer positions, relative to which you can specify the shift in bytes for the next operation.

ENUM\_FILE\_POSITION

| Identifier | Description |
| --- | --- |
| SEEK\_SET | File beginning |
| SEEK\_CUR | Current position of a file pointer |
| SEEK\_END | File end |

See also

[FileIsEnding](fileisending.md), [FileIsLineEnding](fileislineending.md)