Total



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / Total

[![Previous](previous.png)](clistfreemode2.md) 
[![Next](next.png)](clistissorted.md)

Total

Gets the number of elements in the list.

```
int  Total() const
```

Return Value

Number of elements in the list.

Example:

```
//--- example for CList::Total() 
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
   //--- check total 
   int total=list.Total(); 
   //--- use list 
   //--- ... 
   //--- delete list 
   delete list; 
  }
```