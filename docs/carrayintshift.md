Shift



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayInt](carrayint.md) / Shift

[![Previous](previous.png)](carrayintupdate.md) 
[![Next](next.png)](carrayintdelete.md)

Shift

Moves an item from a given position in the array to the specified offset.

```
bool  Shift(
   int  pos,       // position
   int  shift      // shift
   )
```

Parameters

pos

[in]  Position of the moved element in the array

shift

[in]  The shift value (both positive and negative).

Return Value

true - successful, false - cannot move the element.

Example:

```
//--- example for CArrayInt::Shift(int,int)
#include <Arrays\ArrayInt.mqh>
//---
void OnStart()
  {
   CArrayInt *array=new CArrayInt;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- add arrays elements
   //--- . . .
   //--- shift element
   if(!array.Shift(10,-5))
     {
      printf("Shift error");
      delete array;
      return;
     }
   //--- delete array
   delete array;
  }
```