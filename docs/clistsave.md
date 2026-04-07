Save



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / Save

[![Previous](previous.png)](clistsearch.md) 
[![Next](next.png)](clistload.md)

Save

Saves list data in the file.

```
virtual bool  Save(
   int  file_handle      // file handle
   )
```

Parameters

file\_handle

[in] Handle of the binary file previously opened using the FileOpen () function.

Return Value

true - successfully completed, false - error.

Example:

```
//--- example for CList::Save(int) 
#include <Arrays\List.mqh> 
//--- 
void OnStart() 
  { 
   int    file_handle; 
   CList *list=new CList; 
   //--- 
   if(list!=NULL) 
     { 
      printf("Object create error"); 
      return; 
     } 
   //--- add lists elements 
   //--- . . . 
   //--- open file 
   file_handle=FileOpen("MyFile.bin",FILE_WRITE|FILE_BIN|FILE_ANSI); 
   if(file_handle>=0) 
     { 
      if(!list.Save(file_handle)) 
        { 
         //--- file save error 
         printf("File save: Error %d!",GetLastError()); 
         delete list; 
         FileClose(file_handle); 
         //--- 
         return; 
        } 
      FileClose(file_handle); 
     } 
   //--- delete list 
   delete list; 
  }
```