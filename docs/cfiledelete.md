Delete



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / Delete

[![Previous](previous.png)](cfileclose.md) 
[![Next](next.png)](cfileisexist.md)

Delete

Deletes the file assigned to the file instance.

```
void  Delete()
```

Delete

Deletes the specified file.

```
void  Delete(
   const string  file_name      // file name
   )
```

Parameters

file\_name

[in]  File name of the file to delete.

Note

The working folder is dependent on the flag that was previously set/reset using the SetCommon() method.