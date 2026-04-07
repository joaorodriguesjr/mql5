GetLastNode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / GetLastNode

[![Previous](previous.png)](clistgetnextnode.md) 
[![Next](next.png)](clistsort.md)

GetLastNode

Gets the last element of the list.

```
CObject*  GetLastNode()
```

Return Value

Pointer to the last element - success, NULL - cannot get a pointer.

Example:

```
//--- example for CList::GetLastNode() 
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
   //--- add list elements 
   //--- . . . 
   CObject *object=list.GetLastNode(); 
   if(object==NULL) 
     { 
      printf("Get node error"); 
      delete list; 
      return; 
     } 
   //--- use element 
   //--- . . . 
   //--- do not delete element 
   //--- delete list 
   delete list; 
  }
```