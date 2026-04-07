FreeMode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / FreeMode

[![Previous](previous.png)](clist.md) 
[![Next](next.png)](clistfreemode2.md)

FreeMode

Gets the flag of memory management when deleting list elements.

```
bool  FreeMode() const
```

Return Value

Flag of memory management.

Example:

```
//--- example for CList::FreeMode()  
#include <Arrays\List.mqh>  
//---  
void OnStart()  
  {  
   CList *list=new CList;  
   //---  
   if(list==NULL)  
     {  
      printf("Object create error");  
      return;  
     }  
   //--- get free mode flag  
   bool list_free_mode=list.FreeMode();  
   //--- delete list  
   delete list;  
  }
```