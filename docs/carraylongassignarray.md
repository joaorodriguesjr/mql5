AssignArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayLong](carraylong.md) / AssignArray

[![Previous](previous.png)](carraylonginsertarrayconst.md) 
[![Next](next.png)](carraylongassignarrayconst.md)

AssignArray

Copies the elements of one array to another.

```
bool  AssignArray(
   const long&  src[]      // source array
   )
```

Parameters

src[]

[in]  Reference to an array used as a source of elements to copy.

Return Value

true - successful, false - cannot copy the items.

Example:

```
//--- example for CArrayLong::AssignArray(const long &[])
#include <Arrays\ArrayLong.mqh>
//---
long src[];
//---
void OnStart()
  {
   CArrayLong *array=new CArrayLong;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- assign another array
   if(!array.AssignArray(src))
     {
      printf("Array assigned error");
      delete array;
      return;
     }
   //--- use array
   //--- . . .
   //--- delete array
   delete array;
  }
```