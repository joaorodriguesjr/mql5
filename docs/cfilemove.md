Move



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / Move

[![Previous](previous.png)](cfilecopy.md) 
[![Next](next.png)](cfilesize.md)

Move

Renames/moves file.

```
bool  Move(
   const string  src_name,      // file name
   int           src_flag,      // flag
   const string  dst_name,      // file name
   int           dst_flags      // flags
   )
```

Parameters

src\_name

[in]  Source file name.

src\_flag

[in]  Source file flags (only FILE\_COMMON is used).

dst\_name

[in]  File name of the destination file.

dst\_flags

[in]  Flags of the destination file (only FILE\_REWRITE and FILE\_COMMON are used).

Return Value

true - successful, false - failed to move/rename the file.