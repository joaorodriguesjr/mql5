Open



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / Open

[![Previous](previous.png)](cfilesetcommon.md) 
[![Next](next.png)](cfileclose.md)

Open

Opens the specified file and, if it successful, assigns it to the class instance.

```
int  Open(
   const string  file_name,       // file name
   int           flags,           // flags
   short         delimiter=9      // separator
   )
```

Parameters

file\_name

[in]  File name to open.

flags

[in]  File open flags.

delimiter=9

[in]  CSV file separator.

Return Value

Handle of the opened file.

Note

The working folder is dependent on flag that was previously set/reset using the SetCommon() method.