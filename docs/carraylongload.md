Load



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayLong](carraylong.md) / Load

[![Previous](previous.png)](carraylongsave.md) 
[![Next](next.png)](carraylongtype.md)

Load

Loads data array from the file.

```
virtual bool  Load(
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
//--- example for CArrayLong::Load(int)
#include <Arrays\ArrayLong.mqh>
//---
void OnStart()
  {
   int         file_handle;
   CArrayLong *array=new CArrayLong;
   //---
   if(array!=NULL)
     {
      printf("Object create error");
      return;
     }
   //--- open file
   file_handle=FileOpen("MyFile.bin",FILE_READ|FILE_BIN|FILE_ANSI);
   if(file_handle>=0)
     {
      if(!array.Load(file_handle))
        {
         //--- file load error
         printf("File load: Error %d!",GetLastError());
         delete array;
         FileClose(file_handle);
         //---
         return;
        }
      FileClose(file_handle);
     }
   //--- use arrays elements
   for(int i=0;i<array.Total();i++)
     {
      printf("Element[%d] = %I64",i,array.At(i));
     }
   delete array;
  }
```