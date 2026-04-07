GetNextNode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / GetNextNode

[![Previous](previous.png)](clistgetcurrentnode.md) 
[![Next](next.png)](clistgetlastnode.md)

GetNextNode

Gets the next element in the list.

```
CObject*  GetNextNode()
```

Return Value

Pointer to the next element - successful, NULL - cannot get a pointer.

Example:

```
//--- example for CList::GetNextNode() 
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
   CObject *object=list.GetNextNode(); 
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