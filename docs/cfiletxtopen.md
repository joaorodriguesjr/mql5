Open



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileTxt](cfiletxt.md) / Open

[![Previous](previous.png)](cfiletxt.md) 
[![Next](next.png)](cfiletxtwritestring.md)

Open

Opens the specified text file and, if successful, assigns it to the class instance.

```
int  Open(
   const string  file_name,     // file name
   int           flags          // flags
   )
```

Parameters

file\_name

[in]  File name to open.

flags

[in]  File open flags (FILE\_TXT flag is forcibly set).

Return Value

Opened file handle.