Save



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayObj](carrayobj.md) / Save

[![Previous](previous.png)](carrayobjsearchlast.md) 
[![Next](next.png)](carrayobjload.md)

Save

Saves data array in the file.

```
virtual bool  Save(
   int  file_handle      // file handle
   )
```

Parameters

file\_handle

[in] Handle of the binary file previously opened using the FileOpen(...) function.

Return Value

true successfully completed, false - error.

Example:

```
//--- example for CArrayObj::Save(int)
#include <Arrays\ArrayObj.mqh>
//---
void OnStart()
  {
   int        file_handle;
   CArrayObj *array=new CArrayObj;
   //---
   if(array!=NULL)
     {
      printf("Object create error");
      return;
     }
   //--- add arrays elements
   //--- . . .
   //--- open file
   file_handle=FileOpen("MyFile.bin",FILE_WRITE|FILE_BIN|FILE_ANSI);
   if(file_handle>=0)
     {
      if(!array.Save(file_handle))
        {
         //--- file save error
         printf("File save: Error %d!",GetLastError());
         delete array;
         FileClose(file_handle);
         //---
         return;
        }
      FileClose(file_handle);
     }
   delete array;
  }
```