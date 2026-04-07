WriteObject



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFileBin](cfilebin.md) / WriteObject

[![Previous](previous.png)](cfilebinwritedoublearray.md) 
[![Next](next.png)](cfilebinreadchar.md)

WriteObject

Writes data of the CObject class inheritor instance to file.

```
bool  WriteObject(
   CObject*  object      // reference to the object
   )
```

Parameters

object

[in]  Reference to the CObject class inheritor instance to write.

Return Value

true - successful, false - cannot write the data.