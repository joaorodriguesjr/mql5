MoveToIndex



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CList](clist.md) / MoveToIndex

[![Previous](previous.png)](clistsort.md) 
[![Next](next.png)](clistexchange.md)

MoveToIndex

Moves the current element in the list to the specified position.

```
bool  MoveToIndex(
   int  pos      // position
   )
```

Parameters

pos

[in] position in the list to move.

Return Value

true - successful, false - cannot move the element.

Example:

```
//--- example for CList::MoveToIndex(int) 
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
   //--- move current node to begin 
   list.MoveToIndex(0); 
   //--- use list 
   //--- . . . 
   //--- delete list 
   delete list; 
  }
```