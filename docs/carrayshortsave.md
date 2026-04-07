Save



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayShort](carrayshort.md) / Save

[![Previous](previous.png)](carrayshortsearchlinear.md) 
[![Next](next.png)](carrayshortload.md)

Save

Saves data array in the file.

```
virtual bool  Save(
   int  file_handle      // file handle
   )
```

Parameters

file\_handle

[in]  Handle of the binary file previously opened using the FileOpen(...) function.

Return Value

true successfully completed, false - error.

Example:

```
//--- example for CArrayShort::Save(int)
#include <Arrays\ArrayShort.mqh>
//---
void OnStart()
  {
   int          file_handle;
   CArrayShort *array=new CArrayShort;
   //---
   if(array!=NULL)
     {
      printf("Object create error");
      return;
     }
   //--- add 100 arrays elements
   for(int i=0;i<100;i++)
     {
      array.Add(i);
     }
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