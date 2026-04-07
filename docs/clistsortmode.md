SortMode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / SortMode

[![Previous](previous.png)](clistissorted.md) 
[![Next](next.png)](clistcreateelement.md)

SortMode

Gets the version of the sorting.

```
int  SortMode() const
```

Return Value

Sorting mode, or -1 if the list is not sorted.

Example:

```
//--- example for CList::SortMode() 
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
   //--- check sort mode 
   int sort_mode=list.SortMode(); 
   //--- use list 
   //--- ... 
   //--- delete list 
   delete list; 
  }
```